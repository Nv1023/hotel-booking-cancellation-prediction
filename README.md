![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
# 🏨 Hotel Booking Cancellation Prediction

## 📌 Project Overview
This project focuses on predicting whether a customer will cancel their hotel booking using historical booking data. By learning patterns from past reservations, the model helps hotels anticipate cancellations, reduce revenue loss, and improve operational planning.

---

## 🎯 Problem Statement
Hotel booking cancellations negatively affect revenue management and resource allocation.  
The objective of this project is to build a machine learning model that accurately predicts whether a booking will be **cancelled or not**, based on customer and booking-related features.

---

## 🧠 Approach
The project follows an end-to-end machine learning workflow:
- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and evaluation
- Generating predictions for test data

---

## 🛠️ Tech Stack
- **Programming Language**: Python  
- **Libraries**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn  
- **Environment**: Jupyter Notebook

---

## 📊 Dataset Description
The dataset contains historical hotel booking records with features such as:
- Lead time
- Customer type
- Room type and meal plan
- Number of special requests
- Previous cancellations
- Length of stay

## Dataset used to this project
https://www.kaggle.com/competitions/mlp-term-3-2025-kaggle-assignment-2/data

**Target Variable**:
- `is_canceled`
  - `1` → Booking cancelled  
  - `0` → Booking not cancelled  

---

## 🔍 Exploratory Data Analysis
Key insights observed:
- Higher lead times are associated with increased cancellation rates
- Repeat customers are less likely to cancel
- Special requests reduce cancellation probability
- Certain market segments show higher cancellation trends

---

## 🤖 Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier *(if applicable)*

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

The best-performing model was selected based on validation results.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Nv1023/hotel-booking-cancellation-prediction.git
   cd hotel-booking-cancellation-prediction
