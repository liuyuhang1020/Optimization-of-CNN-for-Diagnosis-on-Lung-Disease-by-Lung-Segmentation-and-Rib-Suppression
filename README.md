# Optimization of CNN for Diagnosis on Lung Disease by Lung Segmentation and Rib Suppression

This project is affiliated with the [Business AI Lab at the Information Management Research Centre (IMARC), Nanyang Technological University](https://www.ntu.edu.sg/imarc/business-ai-lab).



-	Co-first authored a paper published at the IEEE academic conference [ISCID 2022](http://iukm.zju.edu.cn) (EI indexed), titled [*Optimization of CNN for Diagnosis on Lung Disease by Lung Segmentation and Rib Suppression*](https://ieeexplore.ieee.org/abstract/document/10029477).

-	In the image preprocessing stage, the original data is enhanced by applying histogram equalization for standardization, and a bilateral low-pass filter is used to reduce image noise.

-	Under the TensorFlow framework, an improved U-Net neural network is used for lung image segmentation and rib image elimination in X-ray films to enhance classification accuracy.

-	The Xception neural network is used to classify the processed images. After preliminary training, some layers are frozen and fine-tuned, ultimately achieving a diagnostic accuracy of 96%.
