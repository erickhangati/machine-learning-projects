# 🧠 MNIST Digit Classification with Neural Networks (NumPy Only)

This project demonstrates how to build and train a simple feedforward neural network from scratch using **NumPy** to classify handwritten digits from the **MNIST dataset**.

Unlike traditional projects that rely on libraries like TensorFlow or PyTorch, this one walks through every step of the neural network manually — helping deepen intuition about how neural nets work under the hood.

---

## 📌 What This Project Covers

- 📦 Data loading and preprocessing (flattening, one-hot encoding, normalization)
- 🔢 Weight and bias initialization
- 🧠 Forward propagation (ReLU + Softmax)
- 🎯 Categorical cross-entropy loss computation
- 🔁 Backpropagation and gradient descent training loop
- 📉 Loss visualization over time
- ✅ Accuracy evaluation on test set
- 🖼️ Visualization of model predictions on real images

---

## 🚀 Results

- **Final Test Accuracy:** ~97.5%
- Achieved using only:
  - NumPy
  - No external machine learning libraries
  - One hidden layer with 128 neurons
  - ReLU and Softmax activations

---

## 📂 File Structure

```
deep-learning/
├── neural-network.ipynb
└── README.md (this file)
```

---

## 🎓 Why This Project Matters

This project shows a deep understanding of how neural networks work by avoiding high-level ML tools and implementing everything manually. It’s a great learning experience — and an excellent portfolio piece for demonstrating:

- Model intuition
- Math-to-code translation
- Debugging from the ground up
- Real-world dataset experience (MNIST)

---

## 🧠 Dataset Info

- **Source:** [MNIST Digits Dataset](http://yann.lecun.com/exdb/mnist/)
- **Classes:** 10 (digits 0 to 9)
- **Shape:** 60,000 training images, 10,000 test images (28×28 grayscale)

---

## ✅ Getting Started

To run the notebook:

1. Clone the repository
2. Install NumPy and Matplotlib
3. Launch `mnist-digit-classification.ipynb` in Jupyter
4. Run all cells to train and test the model
