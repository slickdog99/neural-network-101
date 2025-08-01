# 🧠 Neural Network 101

A beginner-friendly implementation of a **feedforward neural network from scratch** using NumPy — ideal for learning the fundamentals of neural networks **without deep learning libraries** like TensorFlow or PyTorch.

---

## 📌 Features

✅ Forward Propagation  
✅ Activation Functions  
✅ Softmax & Cross-Entropy Loss  
✅ Prediction Logic  
✅ Accuracy Calculation  
✅ Educational Code Comments

---

## 📂 File

- neural_network_101.ipynb – A step-by-step Jupyter Notebook containing the full neural network implementation and walkthrough.

---

## ⚙️ Requirements

- Python 3.x  
- NumPy  
- Jupyter Notebook or Google Colab

---

## 🚀 Getting Started

### ▶️ Run in Google Colab (Recommended)
1. Visit [Google Colab](https://colab.research.google.com/)
2. Upload neural_network_101.ipynb
3. Run the notebook cells sequentially

### 💻 Run Locally

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
jupyter notebook neural_network_101.ipynb
🧮 Sample Functions
python
Copy
Edit
def get_predictions(a2):
    return np.argmax(a2, 0)

def get_accuracy(predictions, y):
    print(predictions, y)
    return np.sum(predictions == y) / y.size
These functions are used to extract predicted labels from the output layer and compute classification accuracy.

🎯 Learning Objectives
By the end of this notebook, you'll understand how to:

Structure a basic neural network

Perform forward propagation using matrix operations

Apply softmax and compute categorical cross-entropy loss

Derive predictions and evaluate accuracy

Understand how the gradient of the loss with respect to Z₂ simplifies to A2 - Y when using softmax + cross-entropy

🗂️ Project Structure
bash
Copy
Edit
📁 neural_network_101/
│
├── neural_network_101.ipynb   # Main notebook
└── README.md                  # Project documentation
📚 References & Inspiration
Derivative of the Softmax Function and the Categorical Cross Entropy Loss — This article helped me understand how the derivative of the softmax function combined with the cross-entropy loss simplifies to a very elegant equation: A2 - Y. Highly recommended for anyone trying to grasp this key concept in backpropagation.

📄 License
This project is licensed under the MIT License — use it freely, modify it, and share it!
