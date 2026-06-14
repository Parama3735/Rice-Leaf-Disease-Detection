# Rice Leaf Disease Detection Using Machine Learning and Deep Learning

## Project Overview

Rice is one of the most important food crops worldwide. Various diseases such as Brown Spot, Bacterial Leaf Blight, and Leaf Smut significantly affect rice yield and quality. Early detection of these diseases helps farmers take preventive measures and minimize crop losses.

This project aims to classify rice leaf diseases using image processing, Machine Learning, and Deep Learning techniques. Multiple models were developed and compared to identify the most effective approach for disease classification.

---

## Problem Statement

Develop an automated rice leaf disease detection system capable of classifying rice leaf images into the following categories:

* Brown Spot
* Bacterial Leaf Blight
* Leaf Smut

The objective is to improve disease diagnosis accuracy and support precision agriculture practices.

---

## Dataset Information

The dataset contains rice leaf images belonging to three disease classes:

| Disease               | Number of Images |
| --------------------- | ---------------- |
| Brown Spot            | 20               |
| Leaf Smut             | 20               |
| Bacterial Leaf Blight | 40               |

The images were preprocessed and resized before model training.

---

## Technologies Used

* Python
* NumPy
* Pandas
* OpenCV
* Matplotlib
* Seaborn
* Scikit-Learn
* TensorFlow
* Keras

---

## Project Workflow

1. Data Collection
2. PDF to Image Conversion
3. Data Loading
4. Exploratory Data Analysis (EDA)
5. Data Visualization
6. Image Preprocessing
7. Feature Engineering
8. Model Training

   * Support Vector Machine (SVM)
   * Random Forest Classifier
   * Convolutional Neural Network (CNN)
9. Hyperparameter Tuning
10. Model Evaluation
11. Model Comparison
12. Final Prediction System

---

## Data Preprocessing

* Image Resizing
* Image Normalization
* Label Encoding
* Train-Test Split
* Data Augmentation

---

## Models Implemented

### 1. Support Vector Machine (SVM)

SVM was used as a baseline machine learning classifier after converting images into numerical feature vectors.

### 2. Random Forest Classifier

Random Forest was used to improve classification performance through ensemble learning.

### 3. Convolutional Neural Network (CNN)

CNN automatically extracts image features and performs disease classification with high accuracy.

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Results

The CNN model achieved the best performance among all tested models due to its ability to learn disease-specific visual patterns directly from images.

| Model         | Performance |
| ------------- | ----------- |
| SVM           | Good        |
| Random Forest | Better      |
| CNN           | Best        |

---

## Conclusion

This project successfully developed a rice leaf disease classification system capable of identifying Brown Spot, Bacterial Leaf Blight, and Leaf Smut diseases from leaf images. Comparative analysis demonstrated that the CNN model outperformed traditional machine learning approaches and is suitable for real-world deployment in smart agriculture applications.

---

## Future Scope

* Mobile Application Integration
* Real-Time Disease Detection
* Larger Dataset Collection
* Transfer Learning Models (ResNet, VGG16, EfficientNet)
* Cloud-Based Agricultural Monitoring Systems

---

## Author

Parasuraman M

Electronics and Communication Engineering (ECE)

Machine Learning | Deep Learning | Computer Vision
