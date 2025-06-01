# 🧠 Handwritten Digit Recognition with MNIST

This beginner-friendly project uses a neural network to recognize handwritten digits (0–9) using the MNIST dataset. The model is trained using TensorFlow/Keras and run in Jupyter Notebook.

---

## 🔍 Problem Statement

Recognizing handwritten digits is one of the classic problems in machine learning and computer vision. It is used in:
- Postal automation (reading ZIP codes)
- Bank check processing
- Digitizing forms or documents

---

## 🧰 Tools & Technologies

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook
- MNIST Dataset

---

## 📊 Dataset

The project uses the MNIST dataset:
- 60,000 training images
- 10,000 testing images
- Each image is 28x28 pixels in grayscale

---

## 🚀 Steps in the Project

1. **Import required libraries**
2. **Load and visualize the MNIST dataset**
3. **Preprocess the data (normalize pixel values)**
4. **Build a neural network using Keras Sequential API**
5. **Train the model on training data**
6. **Evaluate on test data**
7. **Make a prediction on a sample image**
8. *(Optional)* Use your own image as input

---

## 🧠 Model Architecture

- Input Layer: 784 neurons (28x28 pixels flattened)
- Hidden Layer: 128 neurons, ReLU activation
- Output Layer: 10 neurons (for digits 0–9), softmax activation

---

## 📈 Results

- Achieved test accuracy: ~97%
- Example prediction:

![Sample Output](sample_output.png)

---

## 📁 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/digit-recognizer-mnist.git
