# Linear Regression From Scratch

A simple implementation of Linear Regression from scratch in Python using NumPy, without using machine learning libraries such as Scikit-Learn.

## Overview

This project implements a Linear Regression model trained using Gradient Descent to predict salaries based on years of experience.

The model learns the relationship:

y = wx + b

where:

- x = Years of Experience
- y = Salary
- w = Weight (slope)
- b = Bias (intercept)

## Features

- Linear Regression implemented from scratch
- Random weight and bias initialization
- Gradient Descent optimization
- Mean Squared Error (MSE) loss
- Early stopping using convergence threshold
- Visualization of regression line
- Training loss tracking

## Dataset

The project uses the `Salary_Data.csv` dataset containing:

| Feature | Description |
|----------|-------------|
| YearsExperience | Years of professional experience |
| Salary | Salary earned |

## Project Structure

```
Linear_Regressor/
│
├── main.py
├── LR.ipynb
├── Salary_Data.csv
├── requirements.txt
└── README.md
```

## Mathematical Formulation

Prediction:

ŷ = wx + b

Loss Function:

J(w,b) = (1/2n) Σ(y - ŷ)²

Gradients:

∂J/∂w = -(1/n) Σ[(y - ŷ)x]

∂J/∂b = -(1/n) Σ(y - ŷ)

Parameter Updates:

w = w + α * w_grad

b = b + α * b_grad

where α is the learning rate.

## Hyperparameters

| Parameter | Description |
|------------|-------------|
| lr | Learning Rate |
| max_iter | Maximum training iterations |
| threshold | Early stopping threshold |

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

## Run

```bash
python main.py
```

## Example Output

- Training loss decreases over iterations.
- Best-fit regression line is plotted against the dataset.
- Learned weight and bias values are displayed.

## Learning Objectives

This project was built to understand:

- Object-Oriented Programming in Python
- Gradient Descent
- Loss Functions
- Parameter Optimization
- Machine Learning Fundamentals
- NumPy Vectorization

## Future Improvements

- Multiple Linear Regression
- Feature Scaling
- R² Score Evaluation
- Mini-Batch Gradient Descent
- Stochastic Gradient Descent
- Model Saving and Loading

## Author

Sreedevi K

Computer Science Engineering Student  
National Institute of Technology Calicut

LinkedIn:
https://www.linkedin.com/in/sreedevi-k-tech

GitHub:
https://github.com/sreedevi101010