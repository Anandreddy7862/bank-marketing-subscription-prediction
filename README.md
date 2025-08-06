# bank-marketing-subscription-prediction
Developed a logistic regression model to predict client term deposit subscriptions using the Portuguese Bank Marketing dataset. The project analyzes demographic and campaign features to improve marketing targeting, increase conversion rates, and optimize campaign performance.

# 📈 Term Deposit Subscription Prediction – Bank Marketing Data

This project analyzes the **Marketing Campaigns of a Portuguese Banking Institution** using machine learning techniques. The goal is to develop a predictive model that determines whether a client will subscribe to a **term deposit**, enabling better marketing targeting and strategy optimization.
---
## 🔍 Project Overview

- **Dataset:** Bank Marketing Data (UCI Repository)
- **Model Used:** Logistic Regression
- **Goal:** Predict client subscription (`yes` / `no`) based on demographic and campaign data.
---
## 📊 Dataset Description

The dataset contains information collected during direct marketing campaigns (phone calls) of a Portuguese bank. Features include:

- **Demographics:** age, job, marital status, education
- **Campaign Data:** contact type, number of calls, previous outcomes
- **Target Variable:** `y` – whether the client subscribed to a term deposit

---

## 🧪 Workflow Summary

1. **Data Loading & Cleaning**
   - Loaded Excel file
   - Checked for missing values and replaced `'unknown'` with mode values

2. **Exploratory Data Analysis**
   - Visualized distributions of categorical variables
   - Calculated subscription rates

3. **Preprocessing**
   - Selected predictors and target
   - Handled categorical variables
   - Split data into training and test sets

4. **Model Building**
   - Trained a **Logistic Regression** model
   - Evaluated with **Accuracy** and **ROC-AUC**

5. **Evaluation**
   - Accuracy Score
   - ROC Curve

---

## 📈 Results

- Achieved a decent **accuracy** in predicting subscription likelihood
- Visualized performance using **ROC Curve** and calculated **AUC**

---

## ✅ Business Impact

By analyzing client demographics and campaign history, the model enables more effective targeting of marketing efforts. This helps:

- Increase **conversion rates**
- Reduce **marketing costs**
- Improve **campaign ROI**

---

## 🛠 Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **scikit-learn**

---

## 📁 File Structure

- `final_project.py` – Contains the complete code (converted from notebook)
- `bank-full.xlsx` – Source dataset (not included here due to size)

---

## 📌 Future Improvements

- Encode categorical variables using one-hot encoding
- Apply cross-validation
- Try other models: Random Forest, SVM
- Deploy as a web app (e.g., using Streamlit)

---

## 📬 Contact

Feel free to connect or collaborate:

**Anand Reddy**  
📧 [anandkumarreddy7862@gmail.com]  
🔗 [LinkedIn](https://www.linkedin.com/in/venkata-anand-kumar-reddy-arava-015376255/)  
💻 [GitHub](https://github.com/Anandreddy7862)

---


