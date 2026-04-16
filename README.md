# 🌿 Plant Disease Prediction Using CNN (Deep Learning Project)

A deep learning-based image classification system that detects plant diseases from leaf images using a Convolutional Neural Network (CNN). The model is trained on the **PlantVillage Dataset** and can classify **38 different plant disease categories**.

---

## 🚀 Project Overview

This project builds an end-to-end image classification pipeline:

- Dataset: PlantVillage (Color Images)
- Model: Custom CNN (TensorFlow/Keras)
- Task: Multi-class classification (38 classes)
- Goal: Detect plant diseases from leaf images automatically

---

## 📂 Dataset Information

- Dataset Source: Kaggle PlantVillage Dataset  
- Total Classes: **38**
- Image Types: RGB (Color images)
- Input Size: 224 × 224 pixels

Example classes:
- Apple___Apple_scab  
- Tomato___Late_blight  
- Potato___Early_blight  
- Grape___Black_rot  
- Tomato___healthy  

---

## 🧠 Model Architecture

The CNN model consists of:

- Conv2D (32 filters) + MaxPooling
- Conv2D (64 filters) + MaxPooling
- Flatten layer
- Dense layer (256 neurons, ReLU)
- Output layer (Softmax, 38 classes)

### Loss Function:
- Categorical Crossentropy  

### Optimizer:
- Adam  

---

## 📊 Training Details

- Train/Validation Split: 80% / 20%
- Batch Size: 32
- Epochs: 5
- Image Augmentation: Rescaling (1./255)

### Performance:
- Training Accuracy: ~97%
- Validation Accuracy: ~88%

---

## 📈 Results

The model shows good generalization on validation data:

- ✔ Validation Accuracy: **88.28%**
- ✔ Low overfitting after training stabilization

---


