# Mail Classification Using Machine Learning

This project classifies emails as spam or ham (not spam) using natural language processing techniques and a Logistic Regression model.

---

## Overview

The classification system processes email text data and determines whether it is spam or ham. It demonstrates:

- Data preprocessing and label encoding
- Feature extraction using TF-IDF
- Model training and evaluation
- Predictive system for new email messages

---

## Dataset

The dataset contains 5,572 samples with 2 features:
- Category: Spam (0) or Ham (1)
- Message: The email text

Dataset Distribution
- Ham: 4,825 samples
- Spam: 747 samples

---

## Dependencies

Required Python libraries:
- `numpy`
- `pandas`
- `scikit-learn`

---

## Steps

### 1. Data Preprocessing
- Load and clean the dataset.

### 2. Train-Test Split
- Split data into 80% training and 20% testing subsets.

### 3. Feature Extraction
- Transform email text data into numerical feature vectors using TF-IDF.

### 3. Model Training
- Train a Logistic Regression model on the training data.

### 4. Model Evaluation
- Training Accuracy: 96.70%
- Testing Accuracy: 96.59%

### 5. Prediction System
- Classify new email messages as spam or ham based on the trained model.

---

## Usage

1. Clone the repository:
```bash
git clone https://github.com/iDharitri-Raj/Spam_Mail_Prediction
```
2. Install dependencies:
```bash
pip install numpy pandas scikit-learn
```
3. Run the script to train the model and make predictions.
