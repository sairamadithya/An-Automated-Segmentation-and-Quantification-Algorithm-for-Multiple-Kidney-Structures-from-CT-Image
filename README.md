# Kidney-Tumor-and-Structure-Segmentation-using-Deep-Learning
This project is about the development of a deep learning based segmentation algorithm of kidney anatomical parts and tumor from the CT images.

Abstract: Kidney tumor is a malicious disorder, contributing to the 12 th most common cause of death, worldwide. Kidney segmentation is one the important tasks carried out by radiologists during of ailments affecting the kidney, especially tumors. Automated segmentation algorithms can aid clinicians for quicker and better clinical decisions. To develop an algorithm for the segmentation and quantification of kidney, tumor and vasculature from CT images using deep learning. The KiPA dataset is used for this work. The 3D images and masks are normalized and the axial slices are considered for training data. Multiple segmentation algorithms (U-Net, LinkNet, FPN and PSPNet) were developed using multiple CNN backbones. A quantification algorithm was developed by measuring the regional properties. Finally, a user interface was developed to execute the operations in real time. A total of 15 segmentation algorithms trained, the FPN algorithm with the Dense Net backbone produced the highest results of 91% dice score, 94% F1 score, 98.4% accuracy,
98.5% precision, 98.5% recall and 0.9926 AUC scores on the testing set respectively. Hence in this work, a deep learning based algorithm for the automated segmentation and quantification of kidney structures was developed successfully. The proposed work has produced great result and can be of great aid for clinicians for their diagnosis, analysis and treatment of renal ailments.

Tech Stack- OpenCV, Python, Tensorflow, Keras, PyQt5.

Kidneyseg_sit_ui- This is the .ui frontend file of the developed desktop application using PyQt5 tool.

Kidneyseg_sit_py- This is the .py code for running the desktop application. It has both the frontend in PyQt5 and the corresponding backend functions in Python.
