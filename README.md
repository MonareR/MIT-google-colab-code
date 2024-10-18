PPE Compliance Detection using Machine Learning
Overview
This project focuses on developing a machine learning model to detect Personal Protective Equipment (PPE) compliance in various industries, utilizing the SH17 dataset. By employing advanced techniques in Computer Vision and Machine Learning, this study aims to enhance workplace safety and reduce accidents.

Table of Contents
Introduction
Data
Methodology
Preprocessing
Exploratory Data Analysis (EDA)
Model
Findings
Business Value
Conclusion
Getting Started
License
Introduction
Workplace safety is a growing concern in industries like construction, mining, and manufacturing. Personal Protective Equipment (PPE) serves as a crucial line of defense against workplace hazards. This project leverages machine learning techniques to automatically detect PPE compliance, enhancing safety measures in these sectors.

Data
The SH17 dataset, sourced from Kaggle, contains 17 different PPE classes with images, labels, and metadata. It meets the criteria of volume, value, and variety, making it suitable for our analysis.

Methodology
Preprocessing
Data Loading and Structure: The dataset was downloaded and unzipped using Kaggle's API, with images and labels organized in a pandas DataFrame.
Image and Label Preprocessing: Images were normalized and resized to 224x224 pixels, while labels were converted to one-hot vectors.
Exploratory Data Analysis (EDA)
EDA was performed to visualize class frequencies and assess the quality of image-label pairs.

Model
A Convolutional Neural Network (CNN) was employed, featuring:

Convolution Layers: 3 layers with increasing filters (32, 64, 128).
Dense Layer: For representation learning.
Dropout Layer: To minimize overfitting.
Output Layer: Utilizing a sigmoid activation function.
Findings
PPE Class Frequency: Imbalances noted in class representation.
Accuracy vs. Epochs: Achieved 90% validation accuracy, suggesting model reliability.
Confusion Matrices: Most classes were accurately classified, with minimal misclassifications.
Business Value
The model's ability to accurately classify PPE compliance can lead to improved workplace safety, productivity, and efficiency, ultimately resulting in increased business value.

Conclusion
This project successfully built a reliable model for PPE compliance detection, addressing class imbalances and showcasing high accuracy. Future work could focus on enhancing model reliability through techniques aimed at addressing class imbalance.
