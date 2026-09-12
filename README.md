# Uveal-Melanoma-Detection
# Deep Learning-Based Classification of Uveal Melanoma

A deep learning-based medical image classification system for detecting and classifying ocular fundus images into multiple disease categories.

## 📌 Project Overview

This project focuses on the classification of ocular diseases using deep learning and Convolutional Neural Networks (CNNs). The system analyzes fundus images and classifies them into the following four categories:

* **Uveal Melanoma (UM)**
* **Normal**
* **Choroidal Osteoma (CO)**
* **Choroidal Hemangioma (CH)**

Multiple deep learning architectures were evaluated to identify the best-performing model.

## 🧠 Models Evaluated

* MobileNetV2
* EfficientNet-B0
* ResNet-18
* VGG16

Among the evaluated models, **VGG16 achieved the best test accuracy of 88%**.

## ⚙️ Techniques Used

* Data Augmentation
* Class Balancing
* Weighted Random Sampling
* Focal Loss
* Hyperparameter Optimization
* Transfer Learning
* Grad-CAM for Model Explainability

## 📊 Results

The best-performing model achieved:

**Test Accuracy: 88%**

Grad-CAM was also applied to visualize the important regions of fundus images influencing the model's predictions.

## 🛠️ Technologies Used

* Python
* PyTorch
* OpenCV
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Google Colab / Jupyter Notebook

## 🚀 Future Work

* Improve performance using larger and more diverse datasets
* Deploy the model as a web application using Streamlit
* Develop a user-friendly interface for predictions
* Further improve model explainability
* Explore additional CNN and Vision Transformer architectures

## ⚠️ Disclaimer

This project is developed for educational and research purposes only. It is not intended to replace professional medical diagnosis. Final medical decisions should always be made by qualified healthcare professionals.

## 👤 Author

**Haris Azeem**
AI Engineer | Deep Learning & Computer Vision
