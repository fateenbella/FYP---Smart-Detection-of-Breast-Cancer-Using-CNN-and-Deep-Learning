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

Dataset must be downloaded prior to running the preprocessing scripts.(https://www.kaggle.com/datasets/ambarish/breakhis)



🛠 Prerequisites & Tech Stack

Python 3.8+

TensorFlow / Keras

Pandas

OpenCV (cv2)

NumPy

Matplotlib & Seaborn (for result visualization)


🧠 Methodology

Data Preprocessing: Consolidated and standardized 7,909 microscopic images (from 82 patients) from the BreaKHis dataset. Extracted class labels dynamically from nested directory paths to create a unified training pipeline.

Model Training: Trained a Custom CNN as a baseline, followed by fine-tuning EfficientNetB0, DenseNet121, and ResNet50.

Evaluation: Assessed models based on overall accuracy, computational efficiency, and, most importantly, the false-negative rate (recall for malignant cases), given the clinical context.


📈 Key Findings & Results

<img width="337" height="293" alt="image" src="https://github.com/user-attachments/assets/d6117827-7d0d-46a4-a8ca-d049dfbe1753" /> 
<img width="343" height="343" alt="image" src="https://github.com/user-attachments/assets/92dbd117-52af-466b-b460-db78045638ed" />

For CNN

<img width="333" height="298" alt="image" src="https://github.com/user-attachments/assets/f3c2c55b-9de0-464f-9047-27b98a7ec685" />
<img width="341" height="331" alt="image" src="https://github.com/user-attachments/assets/aac653e5-f017-4fb4-af2c-7789dcc5e123" />

For EfficientNetB0

<img width="324" height="282" alt="image" src="https://github.com/user-attachments/assets/0fe35cc7-ec4c-4f53-9d3e-869470919902" />
<img width="346" height="351" alt="image" src="https://github.com/user-attachments/assets/9828f834-c7f6-4ef9-9380-45d0cd615c83" />

For DenseNet121

<img width="344" height="298" alt="image" src="https://github.com/user-attachments/assets/61c174a1-0389-471b-ae81-7c3a7c2ee554" />
<img width="344" height="324" alt="image" src="https://github.com/user-attachments/assets/6b8acf00-4eee-4cf5-b5c8-6ac190b07a69" />

For ResNet50


🎓 Author

Fatin Nabilah binti Ahmad Sabri, Nur Adina Faqiha binti Lokman

Final Year Project, International Islamic University Malaysia (IIUM)

Department of Computer Science (Data Science and Computational Intelligence)


