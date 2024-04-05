# Optimization of CNN for Diagnosis on Lung Disease by Lung Segmentation and Rib Suppression

This project is affiliated with the [Business AI Lab at the Information Management Research Centre (IMARC), Nanyang Technological University](https://www.ntu.edu.sg/imarc/business-ai-lab).

-	Co-first authored a paper published at the IEEE academic conference ISCID 2022 (EI indexed), titled *Optimization of CNN for Diagnosis on Lung Disease by Lung Segmentation and Rib Suppression*.

-	在图片数据预处理环节，通过随机平移、旋转、翻折、剪切等方式对原始数据进行增强，运用直方图均衡化方法对图片亮度和对比度进行标准化，并使用双边低通滤波器减少图像噪声。

-	在TensorFlow框架下，使用改进后的U-Net神经网络对X光片进行肺部影像分割和肋骨影像消除，以提高分类准确率。

-	使用Xception神经网络对处理后的图像进行分类，在初步训练后冻结部分层并进行微调，最终诊断准确率达到96%。
