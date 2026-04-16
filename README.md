# 🌿 CNN-Based Plant Disease Detector

A deep learning-based **Plant Disease Classification System** built using **Convolutional Neural Networks (CNN)** and deployed with a **Streamlit web application**.  
The system automatically classifies plant leaf images into different disease categories to support early detection in agriculture.

---


---

## 🧠 Objective

The purpose of this notebook is to build a **Convolutional Neural Network (CNN)** model that can classify plant leaf images into different disease categories.

---

## 🔬 What is Included in the Notebook

### 📌 Data Processing
- Image dataset loading
- Image resizing (224 × 224)
- Normalization (pixel values scaled to 0–1)
- Train/validation split

---

### 📌 Data Augmentation
To improve generalization, the following techniques were used:
- Rotation
- Horizontal flipping
- Zooming
- Shearing

---

### 📌 Model Architecture (CNN)

The model consists of:

- Convolutional layers (Conv2D)
- MaxPooling layers
- Flatten layer
- Fully connected Dense layers
- Softmax output layer for multi-class classification

---

### 📌 Compilation Settings

- **Optimizer:** Adam  
- **Loss Function:** Categorical Crossentropy  
- **Metrics:** Accuracy  

---

### 📌 Training Process

- Model trained for multiple epochs
- Batch-based learning
- Validation dataset used to monitor overfitting
- Accuracy and loss curves analyzed

---

## 📊 Model Performance

- Training Accuracy: ~90% – 95%
- Validation Accuracy: ~88% – 93%

👉 Performance may vary depending on dataset size and augmentation strategy.

---

## 📈 Key Insights

- Data augmentation significantly improves generalization
- CNN performs well for image-based plant disease detection
- Overfitting can be reduced using dropout and augmentation
- Transfer learning can further improve accuracy (recommended)

---

## 🚀 Future Improvements

- Replace CNN with **EfficientNet / ResNet (Transfer Learning)**
- Hyperparameter tuning
- Add EarlyStopping and ModelCheckpoint
- Increase dataset size
- Add Grad-CAM for explainability

---


