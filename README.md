# 🌳 CART Decision Tree Implementation from Scratch

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-orange.svg)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/status-active-success.svg)](notebooks/DecisionTree-giniindex.ipynb)

A comprehensive, educational implementation of the **CART (Classification and Regression Trees)** algorithm with manual Gini impurity calculations, step-by-step iteration analysis, and automated decision tree generation.

## 🎯 Overview

This project provides a **complete educational implementation** of the CART decision tree algorithm. It demonstrates:

✅ **Manual calculation** of Gini impurity for every possible split  
✅ **Automatic selection** of the best split based on minimum weighted Gini  
✅ **Iterative tree building** with detailed logging for each iteration  
✅ **Visual tree generation** using scikit-learn and matplotlib  
✅ **Step-by-step analysis** perfect for learning and teaching

### Why This Project?

Most decision tree tutorials use black-box libraries. This project **opens the box** and shows you exactly how CART works under the hood, making it ideal for:
- 🎓 Students learning machine learning fundamentals
- 👨‍🏫 Educators teaching decision tree algorithms
- 💻 Developers wanting to understand Gini impurity deeply

---

## ✨ Features

### Core Features
- **Manual Gini Calculations**: Computes Gini(S1), Gini(S2), and weighted GiniSplit for every candidate split
- **Categorical & Numerical Splits**: Handles both types of features automatically
- **Dynamic Iteration 2**: Automatically identifies the best split from Iteration 1 and continues building
- **Impurity-Based Selection**: Chooses the most impure child node for further splitting
- **Complete Logging**: Every calculation is printed with IDs, Gini values, and split criteria

### Visualization
- **Tree Diagram**: Generates `decision_tree.png` with colored nodes
- **Decision Rules**: Exports human-readable IF-THEN rules
- **Accuracy Verification**: Confirms 100% training accuracy

### Educational Value
- **Step-by-Step Output**: Perfect for following the algorithm manually
- **Transparent Calculations**: No hidden magic — see every formula applied
- **Comparison Ready**: Easy to compare manual vs. sklearn results

---

## 📦 Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

