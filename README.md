# Linear Regression: From Scratch vs Scikit-Learn

This repository demonstrates Linear Regression using two different approaches:

1. A custom implementation built from scratch using NumPy and Gradient Descent.
2. An implementation using Scikit-Learn's `LinearRegression` model.

The goal of this project is to understand the mathematical foundations of Linear Regression, implement the algorithm manually, and compare the results with a standard machine learning library.

---

## Features

### From Scratch Implementation (LR.ipynb)

- Custom Linear Regression class
- Random weight and bias initialization
- Gradient Descent optimization
- Mean Squared Error (MSE) loss
- Early stopping using convergence threshold
- Training loss tracking
- Regression line visualization

### Scikit-Learn Implementation (lr_scikit.ipynb)

- LinearRegression model from Scikit-Learn
- Model training and prediction
- Regression line visualization
- Comparison with custom implementation

---

## Dataset

The project uses the Salary Dataset containing:

| Feature | Description |
|----------|-------------|
| YearsExperience | Years of professional experience |
| Salary | Salary earned |

The objective is to predict salary based on years of experience.

---

## Project Structure

```text
Linear_Regressor/
│
├── LR.ipynb              # Linear Regression implemented from scratch
├── lr_scikit.ipynb       # Linear Regression using Scikit-Learn
├── Salary_Data.csv       # Dataset
├── requirements.txt      # Project dependencies
└── README.md
```

---

## Mathematical Formulation

### Prediction Function

ŷ = wx + b

where:

- x = Input feature (Years of Experience)
- ŷ = Predicted Salary
- w = Weight (slope)
- b = Bias (intercept)

### Loss Function

J(w,b) = (1/2n) Σ(y - ŷ)²

### Gradient Computation

∂J/∂w = -(1/n) Σ[(y - ŷ)x]

∂J/∂b = -(1/n) Σ(y - ŷ)

### Parameter Updates

w = w + α · w_grad

b = b + α · b_grad

where α is the learning rate.

---

## Hyperparameters

| Parameter | Description |
|------------|-------------|
| lr | Learning Rate |
| max_iter | Maximum training iterations |
| threshold | Convergence threshold for early stopping |

---

## Installation

Clone the repository:

```bash
git clone https://github.com/sreedevi101010/Linear_Regressor.git
cd Linear_Regressor
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Dependencies

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

---

## Running the Project

### From Scratch Implementation

Open and run:

```bash
LR.ipynb
```

### Scikit-Learn Implementation

Open and run:

```bash
lr_scikit.ipynb
```

---

## Learning Outcomes

This project helped in understanding:

- Linear Regression fundamentals
- Gradient Descent optimization
- Mean Squared Error (MSE)
- Parameter updates using gradients
- Object-Oriented Programming in Python
- NumPy vectorized operations
- Data normalization and preprocessing
- Comparison between custom ML implementations and Scikit-Learn

---

## Future Improvements

- Multiple Linear Regression
- Polynomial Regression
- Feature Scaling Pipelines
- R² Score Evaluation
- Mini-Batch Gradient Descent
- Stochastic Gradient Descent
- Model Serialization and Deployment

---

## Author

**Sreedevi K**

Computer Science Engineering Student  
National Institute of Technology Calicut

LinkedIn: https://www.linkedin.com/in/sreedevi-k-tech

GitHub: https://github.com/sreedevi101010
