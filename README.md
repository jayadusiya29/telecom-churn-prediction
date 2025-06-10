# Telecom Customer Churn Prediction 📉📞

This project builds a simple **Decision Tree Classifier** to predict customer churn for a telecom company. Churn refers to when a customer stops doing business with the company. By predicting churn, companies can take proactive steps to retain customers and reduce revenue loss.

---

## 📁 Dataset Description

The dataset is synthetic and simulates telecom customer behavior. It contains the following fields:

| Column               | Description                                     |
|----------------------|-------------------------------------------------|
| `CustomerID`         | Unique identifier for each customer             |
| `Age`                | Age of the customer                             |
| `MonthlyCharge`      | Monthly bill amount                             |
| `CustomerServiceCalls` | Number of times the customer contacted support |
| `Churn`              | Whether the customer churned (`Yes` or `No`)    |

---

## 🧠 Model

We use a **Decision Tree Classifier** from `scikit-learn` to train on 70% of the data and test on 30%. The model predicts whether a customer is likely to churn based on their age, monthly charge, and number of service calls.

---

## 📊 Results

The model is evaluated using **accuracy score** and is also **visualized using `matplotlib` and `sklearn.tree.plot_tree()`** to interpret the decision paths.
