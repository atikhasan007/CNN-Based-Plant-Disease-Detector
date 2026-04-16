# 🌿 CNN-Based Plant Disease Detector

A deep learning-based **Plant Disease Classification System** built using **Convolutional Neural Networks (CNN)** and deployed with a **Streamlit web application**.  
The system automatically classifies plant leaf images into different disease categories to support early detection in agriculture.

---

## 🚀 Project Overview

This project uses a **CNN-based deep learning model** trained on plant leaf images to detect plant diseases.

Users can upload an image, and the model will predict the disease class in real-time using a simple web interface built with Streamlit.

---

## 🧠 Model Details

- **Model Type:** Convolutional Neural Network (CNN)
- **Framework:** TensorFlow / Keras
- **Input Shape:** 224 × 224 × 3
- **Output Activation:** Softmax
- **Loss Function:** Categorical Crossentropy
- **Optimizer:** Adam
- **Task Type:** Multi-class Image Classification

---

## 📊 Model Performance (Typical CNN Results)

Depending on dataset quality and training setup:

- **Basic CNN Model Accuracy:** ~85% – 92%
- **Improved CNN (with Augmentation):** ~90% – 95%
- **Transfer Learning Models (Recommended):**
  - MobileNetV2 → ~94% – 97%
  - ResNet50 → ~95% – 98%
  - EfficientNetB0 → ~96% – 99% (Best Performance)

👉 *For production-level accuracy, transfer learning models (EfficientNet / ResNet) are highly recommended.*

---

## 📌 Training Summary

The model was trained using a labeled plant disease dataset with the following pipeline:

- Image loading and resizing (224×224)
- Data normalization (0–1 scaling)
- Data augmentation (rotation, zoom, flip)
- CNN architecture design
- Model training with validation split
- Performance evaluation using accuracy and loss curves
- Model saved in `.h5` format

---

## 📷 How It Works

1. Upload a plant leaf image (JPG / PNG)
2. Image is resized to 224 × 224
3. Preprocessing and normalization applied
4. CNN model predicts probabilities for each class
5. Highest probability class is selected
6. Result is shown in the Streamlit UI

---

## 🧾 Example Output Classes

- Healthy
- Rust
- Powdery Mildew
- Leaf Spot
- Blight
- Early Blight
- Late Blight

*(Classes depend on dataset used for training)*

---

## 🛠️ Tech Stack

- Python 🐍  
- TensorFlow / Keras 🤖  
- NumPy  
- Pillow (PIL)  
- Streamlit 🌐  
- Matplotlib (for training visualization)

---

## 📈 Key Features

- 🌱 Real-time plant disease detection  
- ⚡ Fast prediction using CNN model  
- 🖥️ Simple and interactive Streamlit UI  
- 📊 Image preprocessing pipeline  
- 🧠 Deep learning-based classification  

---

## 🔬 Recommended Improvements

To improve accuracy and performance:

- Use **Transfer Learning (Highly Recommended)**
  - EfficientNetB0 / B1
  - ResNet50
  - MobileNetV2
- Increase dataset size and diversity
- Apply stronger augmentation techniques
- Fine-tune pretrained models
- Add model explainability (Grad-CAM visualization)
- Deploy using cloud platforms (Streamlit Cloud / HuggingFace / AWS)

---

## 📊 Expected Accuracy Guide

| Model Type              | Expected Accuracy |
|------------------------|------------------|
| Simple CNN             | 85% – 92%        |
| CNN + Augmentation     | 90% – 95%        |
| MobileNetV2           | 94% – 97%        |
| ResNet50              | 95% – 98%        |
| EfficientNetB0        | 96% – 99%        |

---

## 👨‍💻 Author

**Md Atik Hasan**

- GitHub: https://github.com/atikhasan007  
- Email: imatik513@gmail.com  

---


