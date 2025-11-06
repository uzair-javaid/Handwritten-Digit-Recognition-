# 🔢 Handwritten Digit Recognition using MNIST Dataset

This project builds a **Neural Network model** to recognize handwritten digits (0–9) using the **MNIST dataset**.
It includes two scripts: one for **training** the model and another for **making predictions**.

---

## 🧠 Project Overview

The MNIST dataset is one of the most popular beginner datasets in Machine Learning.
It contains 70,000 grayscale images (28x28 pixels) of handwritten digits from **0 to 9**.

This project:

* Loads and preprocesses the MNIST dataset
* Builds and trains a **Neural Network** using TensorFlow/Keras
* Evaluates accuracy on the test set
* Saves the trained model
* Loads the saved model to predict digits on unseen data

---

## 📂 Project Structure

```
📁 mnist-digit-recognition/
│
├── mnist_train.py       # Training and saving the model
├── mnist_predict.py     # Loading and predicting digits
├── mnist_digit_recognizer.h5  # Saved model file (after training)
└── README.md            # Project documentation
```

---



## 📈 Sample Output

```
✅ Model loaded successfully!
Predicted: 7 | Actual: 7
🧠 Model Prediction: 7
✅ Actual Label: 7
```


---

## 🧩 Dataset

The dataset is **automatically downloaded** by TensorFlow using:

```python
from tensorflow.keras.datasets import mnist
```

**Dataset Info:**

* Training samples: 60,000
* Testing samples: 10,000
* Image size: 28x28 (Grayscale)

---

## 👨‍💻 Author

**Uzair Javaid**
Final-year Computer Science student passionate about Machine Learning and AI-based solutions.

