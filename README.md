# CART Decision Tree Implementation from Scratch

This project demonstrates a step-by-step implementation of the **CART (Classification and Regression Trees)** algorithm using the **Gini Impurity** metric. It manually calculates the best splits for Iteration 1 and Iteration 2, and then generates a visual decision tree using `scikit-learn`.

## 📊 Dataset
The model is trained on a small dataset of 8 records with 4 features and 1 target variable:
- **Features:** `computer` (categorical), `income` (numerical), `price` (numerical), `student` (boolean)
- **Target:** `BUY` (yes/no)

## 🚀 Features
- **Manual Gini Calculations:** Iterates through all categorical and numerical splits to compute `Gini(S1)`, `Gini(S2)`, and the weighted `GiniSplit`.
- **Dynamic Iteration 2:** Automatically identifies the best split from Iteration 1, isolates the most impure child node, and evaluates all possible splits for Iteration 2.
- **Tree Visualization:** Automatically generates and saves a visual decision tree (`decision_tree.png`) using `matplotlib` and `scikit-learn`.

## 🛠️ Requirements
Make sure you have Python 3.8+ installed. Install the required packages using:
```bash
pip install -r requirements.txt
