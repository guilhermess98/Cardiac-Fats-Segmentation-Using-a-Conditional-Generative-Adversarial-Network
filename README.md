# Cardiac-Fats-Segmentation-Using-a-Conditional-Generative-Adversarial-Network

## Abstract

In recent years, studies have shown that increases in the amount of fat surrounding the human heart are associated to a higher risk of triggering some cardiovascular diseases such as atrial fibrillation and coronary heart disease. Manual segmentation of these fats has not been widely implemented in clinical practice due to the human workload required and the high cost of physicians and technicians. Therefore, the need to perform a quantitative analysis more accurately and faster has driven the development of new computational methods for fat segmentation. In this work, a new deep learning and unified methodology for the autonomous segmentation and quantification of two types of cardiac fats is proposed. We use the pix2pix, a generative conditional adversary network ideally created to perform image-to-image translation. One of the objectives of this work is to analyse how the network behaves in this type of problem, as it was not designed to seamlessly work with it. The segmented fats of the human heart are called epicardial and mediastinal and are separated by the pericardium. Experimental results obtained an average accuracy in relation to the epicardial and mediastinal fats of 99.08% and a true positive of 99.34%. The F<sub>1</sub> score and IoU were, in average, 99.28% and 98.59%, respectively. The proposed approach outperformed most works in the literature and is the current fastest approach.

## pix2pix

For more information about pix2pix and how to use it, please access https://phillipi.github.io/pix2pix/.
