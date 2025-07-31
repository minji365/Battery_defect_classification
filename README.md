# 🔋 Battery Defect Detection with VGG16

This project detects battery cell defects using convolutional neural networks (CNN), particularly VGG16 via transfer learning.

## 📌 Overview
- Binary classification: **Defective** vs. **Normal** battery cell
- Preprocessing: resizing, normalization, augmentation
- Transfer learning using VGG16

## 🧠 Model
- Pretrained VGG16 with custom dense layers
- Frozen base layers, fine-tuning last few layers
- Trained with categorical crossentropy loss and Adam optimizer

## 🛠️ Tools
- Python, TensorFlow/Keras
- Matplotlib, NumPy
- Google Colab 
