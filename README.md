
# 🚀 Optimization Algorithms in Deep Learning

Welcome to my Optimization Algorithms repository!

This repository focuses on understanding, implementing, and comparing different optimization algorithms used in Machine Learning and Deep Learning.

The main objective is to understand how optimizers update model parameters, minimize the loss function, and improve the training process.

## 🎯 Objectives

- Understand the fundamentals of optimization algorithms.
- Implement optimizers from scratch using Python.
- Understand weight and bias updates.
- Explore different gradient descent techniques.
- Compare the performance of different optimizers.
- Analyze convergence speed and training stability.

## 📚 Topics Covered

### 1. Gradient Descent (GD)
Implementation of Batch Gradient Descent, where the entire training dataset is used to calculate the gradient before updating model parameters.

### 2. Stochastic Gradient Descent (SGD)
Implementation of Stochastic Gradient Descent, where model parameters are updated using one training sample at a time.

### 3. Mini-Batch Gradient Descent
Implementation of Mini-Batch Gradient Descent, where a small batch of training samples is used for each parameter update.

### 4. Momentum Optimizer
Implementation of Momentum, which uses previous gradients to accelerate convergence and reduce oscillations.

### 5. RMSprop Optimizer
Implementation of RMSprop, which adapts the learning rate for each parameter using a moving average of squared gradients.

### 6. Adam Optimizer
Implementation of Adam (Adaptive Moment Estimation), which combines Momentum and RMSprop using first and second moment estimates.

### 7. AdamW Optimizer
Implementation of AdamW, which uses decoupled weight decay to improve regularization and generalization.

### 8. Optimizer Comparison
Compare different optimization algorithms based on:
- Convergence Speed
- Training Loss
- Validation Loss
- Accuracy
- Computational Efficiency
- Training Stability

## 🛠️ Technologies Used

- Python
- NumPy
- Matplotlib
- Pandas
- PyTorch
- Scikit-learn

## 📂 Repository Structure

```text
Optimization-Algorithms/
│
├── 01_Gradient_Descent/
│   └── gradient_descent.py
│
├── 02_Stochastic_Gradient_Descent/
│   └── sgd.py
│
├── 03_Mini_Batch_Gradient_Descent/
│   └── mini_batch_gd.py
│
├── 04_Momentum/
│   └── momentum.py
│
├── 05_RMSprop/
│   └── rmsprop.py
│
├── 06_Adam/
│   └── adam.py
│
├── 07_AdamW/
│   └── adamw.py
│
├── 08_Optimizer_Comparison/
│   ├── comparison.py
│   └── results/
│
├── Images/
│
└── README.md
```

## 📈 Optimizer Comparison

The following table summarizes the main characteristics of the optimizers covered in this repository.

| Optimizer | Adaptive LR | Momentum |
|---|---|---|
| Gradient Descent | No | No |
| SGD | No | No |
| Mini-Batch GD | No | No |
| Momentum | No | Yes |
| RMSprop | Yes | No |
| Adam | Yes | Yes |
| AdamW | Yes | Yes |

## ⚙️ Installation

Clone this repository:

```bash
git clone https://github.com/Arafat-shuvo/Optimization-Algorithms.git
```

Navigate to the project directory:

```bash
cd Optimization-Algorithms
```

Install the required libraries:

```bash
pip install numpy matplotlib pandas torch scikit-learn
```

## ▶️ How to Run

For example, to run Gradient Descent:

```bash
python 01_Gradient_Descent/gradient_descent.py
```

To run the optimizer comparison:

```bash
python 08_Optimizer_Comparison/comparison.py
```

## 📊 Visualization

This repository will include visual comparisons such as:

- Loss vs. Epochs
- Convergence Curves
- Learning Rate Analysis
- Parameter Update Visualization
- Optimizer Performance Comparison

## 🎓 Learning Outcomes

After completing this repository, I aim to:

- Understand how different optimizers work mathematically.
- Implement optimization algorithms from scratch.
- Understand the role of learning rates and gradients.
- Analyze convergence behavior.
- Select appropriate optimizers for different Deep Learning tasks.

## 🚀 Future Plans

- Implement advanced optimizers.
- Experiment with different learning rates.
- Compare optimizers using CNN architectures.
- Test optimizers on image classification and segmentation tasks.
- Develop and evaluate a new optimization algorithm.

## 👨‍💻 Author

**Md. Arafat Hossain**

- GitHub: [Arafat-shuvo](https://github.com/Arafat-shuvo)

---

⭐ If you find this repository useful, feel free to give it a star!
