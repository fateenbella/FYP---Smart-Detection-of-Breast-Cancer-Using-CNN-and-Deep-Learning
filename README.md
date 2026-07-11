# FYP---Smart-Detection-of-Breast-Cancer-Using-CNN-and-Deep-Learning

This repository contains the code and methodology for evaluating and classifying histopathological images to improve early breast cancer detection. It compares a Custom Convolutional Neural Network (CNN) against three pre-trained transfer learning architectures (EfficientNetB0, DenseNet121, and ResNet50) to address the high false-positive rates often seen in traditional mammography.



📖 Overview

The primary objective of this research is to develop an image processing and deep learning methodology capable of accurately classifying breast tumors as either benign or malignant.

Key Findings:

Transfer Learning Dominance: Pre-trained models significantly outperformed the Custom CNN in terms of accuracy and class separation.

Top Accuracy: EfficientNetB0 achieved the highest overall accuracy at 94%, closely followed by DenseNet121 at 93%.

Clinical Reliability: DenseNet121 was identified as the superior model for clinical application. It minimized critical false negatives (recording only 2 instances) and achieved the highest recall for malignant cases.

Computational Efficiency: While less accurate, the Custom CNN remained the most computationally efficient regarding training duration and inference latency.

📊 Dataset

This project utilizes the BreaKHis dataset, which comprises 7,909 microscopic images from 82 patients.

The images are divided into two primary classes: Benign and Malignant.

Dataset must be downloaded prior to running the preprocessing scripts. (Note: Add the download link or Kaggle reference here if applicable).


🛠 Prerequisites & Tech Stack
Ensure you have the following installed to reproduce the environment:

Python 3.8+

TensorFlow / Keras

Pandas

OpenCV (cv2)

NumPy

Matplotlib & Seaborn (for result visualization)
