# 🐍 SnakeVisionNet – Indian Snake Species Classifier Using MobileNetV2

### 🔬 A Deep Learning-based Classifier to Identify Indian Snake Species with MobileNetV2

---

## 🧪 Case Study

In India, it's estimated that around **50,000 people die annually from snakebites**, out of an estimated **3–4 million snakebite cases**, according to PIB. This accounts for nearly **50% of global snakebite deaths**. However, due to underreporting, the actual number could be much higher.

Early identification of snake species can significantly aid in **administering correct antivenom**, improving survival chances. This project aims to **classify Indian snake species using a lightweight deep learning model** – MobileNetV2 – that can run on mobile and edge devices.

---

## 🧠 Model Architecture

- **Base Model**: MobileNetV2 (pre-trained on ImageNet)
- **Top Layers**:
  - GlobalAveragePooling
  - Dense (ReLU)
  - Dropout
  - Final Dense (Softmax)

> Optimized for **low-latency, high-accuracy performance** on real-world snake images.

---

## 📊 Goal

🎯 **Increase classification accuracy above 80%**

---

## 🖼️ Dataset

You can download the image dataset from the link below:

👉 [**Download Dataset from Google Drive**](https://drive.google.com/drive/folders/1IONnTeknXRj-kKOaWl52aQmwwt01Vj91?usp=drive_link)

> After downloading, place the dataset in a folder named `dataset/` in your project directory.

---
##📈 Training Details
Optimizer: Adam (lr=0.0001)

Loss: Categorical Crossentropy

Metrics: Accuracy

Callbacks: EarlyStopping, ModelCheckpoint, ReduceLROnPlateau

## Features
Real-time prediction with trained .keras model

Lightweight and fast due to MobileNetV2

High potential for field deployment in rural clinics or emergency responders

##📌 To-Do
 Improve accuracy to above 80%

 Add a Flask web interface for demo

 Deploy model on Android using TensorFlow Lite

 Expand dataset with more species & images



