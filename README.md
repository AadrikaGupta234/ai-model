# Credit Card Fraud Detection Using Machine Learning

A beginner-friendly machine learning project that detects fraudulent credit card transactions using Logistic Regression and Decision Tree classifiers.

## Dataset

This project uses the [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

The dataset is **not included** in this repository due to its large size (143 MB). It will be **downloaded automatically** when you run the notebook.

## How to Run

1. **Clone this repository:**
   ```bash
   git clone https://github.com/AadrikaGupta234/ai-model.git
   cd ai-model
   ```

2. **Install dependencies:**
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn kagglehub jupyter
   ```

3. **Open the notebook:**
   ```bash
   jupyter notebook Credit_Card_Fraud_Detection.ipynb
   ```

4. **Run all cells** from top to bottom. The first cell will automatically download the dataset from Kaggle.

> **Note:** On first run, `kagglehub` may ask for your Kaggle credentials. You can get your API key from [kaggle.com/settings](https://www.kaggle.com/settings) → "Create New Token".

## Project Overview

| Step | Description |
|------|-------------|
| 1 | Download dataset from Kaggle |
| 2 | Import libraries |
| 3 | Load and explore the dataset |
| 4 | Basic data analysis (shape, nulls, class counts) |
| 5 | Exploratory Data Analysis (visualizations) |
| 6 | Understand class imbalance |
| 7 | Data preprocessing (scaling, train/test split) |
| 8 | Train Logistic Regression and Decision Tree |
| 9 | Evaluate models (Accuracy, Precision, Recall, F1, Confusion Matrix) |
| 10 | Why accuracy alone is not enough |
| 11 | Conclusion |

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub
