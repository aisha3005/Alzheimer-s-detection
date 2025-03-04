# 🧠 Detection of Alzheimer’s Disease Using Machine Learning
## Introduction
Alzheimer’s Disease (AD) is a progressive neurodegenerative disorder that primarily affects memory, thinking skills, and behavior. It is one of the leading causes of dementia, particularly in individuals over the age of 60. Since there is no cure for AD, early detection is crucial in managing and slowing its progression.

Our project implements Machine Learning techniques to detect Alzheimer’s at an early stage using MRI scans. By leveraging data science and AI, we aim to classify brain scans and provide a comparative analysis of different ML algorithms to determine the most accurate detection method.

Project Objective
The goal of this project is to develop a machine learning-based diagnostic model to identify Alzheimer’s Disease in its early stages using MRI imaging.

## Key Objectives:
✅ Validate the effectiveness of Machine Learning models in AD detection.
✅ Compare different ML algorithms to determine the most accurate one.
✅ Utilize MRI scans for image-based diagnosis.
✅ Improve accuracy by optimizing feature selection.
✅ Implement a user-friendly GUI-based detection system.

## Methodology & Implementation 🔬
### Dataset & Preprocessing
We used MRI brain scan datasets from sources like Kaggle and OASIS (Open Access Series of Imaging Studies). The dataset was cleaned and preprocessed using:
Feature Selection: Selecting the most important features from MRI scans.
Normalization & Scaling: Ensuring uniform data distribution.
Data Augmentation: Expanding the dataset for better model training.

### Machine Learning Algorithms Used
To identify Alzheimer’s Disease, we implemented and compared multiple Machine Learning models:

📌 K-Nearest Neighbors (KNN)
Finds the K-nearest data points and classifies accordingly.
Simple but effective in pattern recognition.
📌 Naïve Bayes
Uses Bayesian probability to classify images.
Assumes feature independence for fast processing.
📌 Random Forest
An ensemble learning technique using multiple decision trees.
Provides high accuracy with reduced overfitting.
📌 AdaBoost
Boosting technique that combines weak learners into a strong model.
Improves model precision while reducing bias.
📌 Gradient Boosting Classifier (GBC)
Uses gradient descent to minimize errors iteratively.
Effective for handling complex datasets.
📌 Extreme Gradient Boosting (XGBoost)
One of the most powerful boosting algorithms.
Optimized for speed and performance.
Results & Performance 📊
We evaluated the models using confusion matrices, classification reports, and ROC curves.

![image](https://github.com/user-attachments/assets/aa2583be-1d12-4de2-9a1b-49721737fc90)

🔍 Key Findings
📌 XGBoost performed the best with an accuracy of 92.3%, making it the most reliable model.
📌 Random Forest & Gradient Boosting also showed strong performance.
📌 Naïve Bayes had the lowest accuracy, indicating it may not be the best approach for this dataset.

Future Scope & Improvements 🚀
🔹 Deep Learning Integration: Implement CNNs (Convolutional Neural Networks) for better image classification.
🔹 Incorporating 3D Brain MRI scans for more robust analysis.
🔹 Cloud-based real-time detection system for Alzheimer’s prediction.
🔹 Enhancing feature engineering using AI-driven methods.
🔹 Developing a mobile app for easy and accessible diagnosis.

### SCREENSHOTS - 
![image](https://github.com/user-attachments/assets/a4fa2812-7d5d-44cd-ba95-3cd33e3c8c8a)

![image](https://github.com/user-attachments/assets/c312ad4d-090d-4c8a-b758-d5c9c74880fb)

![image](https://github.com/user-attachments/assets/8167307c-aa7f-4218-ba19-9a8099dc1846)

![image](https://github.com/user-attachments/assets/b92932bc-4dbd-421b-882b-195b1b834fe1)



Conclusion 🏆
Our project successfully demonstrates how Machine Learning can be used for early Alzheimer’s Disease detection. By comparing various ML models, we found that XGBoost provides the highest accuracy (92.3%), making it the most effective approach.

This research paves the way for AI-powered medical diagnosis, ultimately helping in early detection and treatment. While Alzheimer’s has no cure, early intervention can slow its progression, improving the quality of life for millions.
