# 🧠 Handwritten Digit Recognition using CNN (MNIST)

This project implements a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras** to recognize handwritten digits from the **MNIST dataset**.  
The model is trained to classify digits from **0 to 9** with high accuracy and also supports **custom image prediction**.

---

## 📌 Project Features
- CNN-based digit classification
- Trained on MNIST dataset (60,000 train + 10,000 test images)
- Achieves ~98–99% accuracy
- Supports prediction on **custom handwritten images**
- Implemented and tested using **Google Colab**

---

## 🗂 Dataset
**MNIST Dataset**
- 28 × 28 grayscale images
- 10 classes (digits 0–9)
- Standard benchmark dataset for computer vision

Dataset is automatically loaded using:
```python
tf.keras.datasets.mnist.load_data()
