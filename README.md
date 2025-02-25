# Handwritten Digit Classification using ANN

## 📌 Project Overview
This project implements a **Handwritten Digit Classification** system using an **Artificial Neural Network (ANN)**. The model is trained on the **MNIST dataset**, which contains 28x28 grayscale images of digits (0-9). The goal is to classify the digits accurately using a neural network.

## 🏗️ Technologies Used
- **Python**
- **TensorFlow/Keras**
- **NumPy**
- **Matplotlib**
- **Scikit-Learn**

## 🔗 Google Colab Notebook
You can run this project directly on **Google Colab** using the following link:
[Handwritten Digit Classification - Colab](https://colab.research.google.com/drive/1SqETl3Zi1EEesdJfEv6_QimB-M-YjKGx?usp=sharing#scrollTo=jr2MuKsKRH5G)

## 📊 Dataset
- The **MNIST dataset** consists of **60,000 training images** and **10,000 test images**.
- Each image is **28x28 pixels** in grayscale.
- Labels range from **0 to 9**.

## 🔥 Model Architecture
The ANN model consists of:
- **Input Layer**: 784 neurons (28x28 pixels flattened)
- **Hidden Layers**:
  - 128 neurons with ReLU activation
  - 64 neurons with ReLU activation
- **Output Layer**: 10 neurons with Softmax activation (for multi-class classification)

## 📈 Results & Performance
- The trained ANN achieves **98%+ accuracy** on the MNIST dataset.
- Performance metrics like **Confusion Matrix, Precision, Recall, and F1-score** can be computed within the Colab notebook.

## 🎯 Future Improvements
- Experiment with **CNN models** for better accuracy.
- Train on **larger datasets** like EMNIST for better generalization.
- Deploy the model as a **web application** using Flask or FastAPI.

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

## 📜 License
This project is licensed under the **MIT License**.

---
Developed by **Jigar Vyas** 🚀

