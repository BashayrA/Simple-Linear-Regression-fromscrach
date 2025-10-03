# 📊 Simple Linear Regression

## 🧠 Introduction

This notebook implements a Simple Linear Regression model using **gradient descent** as the optimization algorithm and **Mean Squared Error (MSE)** as the loss function. To ensure comprehensive understanding and model correctness, gradient descent is implemented in two versions:

- A **manual loop-based version**
- A **vectorized NumPy version**

Additionally, the model is wrapped in a **class-based implementation** to support modularity and future deployment as I progress through my Machine Learning course.

---

## 🧪 Methodology

This notebook employs three methodologies to ensure thorough understanding and results verification:

### 1. Gradient Descent  
A step-by-step guide to computing gradients, adjusting learning rates, and minimizing loss values as close to zero as possible.

### 2. Analytical Solution  
The regression problem is also solved using the **closed-form least squares method**, as validated in the STAT301 course. This provides a benchmark for verifying gradient descent results.

### 3. sklearn  
The `LinearRegression` model from `sklearn` is used for comparison, as referenced in the AI221 textbook. This helps validate the custom implementation against a trusted library.

---

## 📚 Contents

- **Requirements**  
  Libraries and setup instructions

- **Model Implementation**  
  Manual and vectorized gradient descent, class-based design

- **Training and Evaluation Metrics**  
  MSE loss tracking, weight updates, performance comparison

- **Code Logic Explanation**  
  Annotated walkthrough of each step in the algorithm

---

## 🚀 Future Plans

- Automate hyperparameter tuning using grid search
- Save and load best-performing models
- Explore activation functions to stabilize gradients
- Extend to multivariate regression and regularization

---