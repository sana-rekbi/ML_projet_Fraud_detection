# Credit Card Fraud Detection

This repository contains a project focused on detecting fraudulent credit card transactions using machine learning techniques. The goal is to develop a model that can accurately classify transactions as fraudulent or legitimate.

---

## Dataset

The dataset used in this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download) from Kaggle. This dataset contains transactions made by European cardholders in September 2013.

- **Number of transactions**: 284,807
- **Fraudulent transactions**: 492
- **Class distribution**: Highly imbalanced (fraudulent transactions represent only 0.172% of all transactions)

## Methodology

1. **Data Preprocessing**:
   - Handled class imbalance using oversampling techniques like SMOTE.
   - Normalized numerical features for better model performance.
   - Splitted the data into training and testing sets.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized the class imbalance.
   - Analyzed correlations between features.

3. **Modeling**:
   - Used machine learning algorithms such as Logistic Regression, Random Forest, and Gradient Boosting.
   - Evaluated performance using metrics like Accuracy, Precision, Recall, and F1-Score.

4. **Evaluation**:
   - Focused on Recall to minimize false negatives (undetected frauds).

