# 📊 PwC Churn Analysis Project

![image](https://github.com/user-attachments/assets/e3981a05-5db8-4828-8f36-7efd8ec6922c)

## 📊 Project Overview

This project is a hypothetical case study where I take on the role of a data consultant working on behalf of PwC’s Data & Analytics Consulting Division. The scenario involves a leading telecom company experiencing a high customer churn rate. In this setup, PwC has been engaged to analyze churn patterns, uncover key drivers, and propose data-driven strategies to improve customer retention.

## 🧩 Business Context

The telecom industry is highly competitive, with customers frequently switching providers for better pricing, improved service quality, or a more seamless customer experience. In this scenario, the company is losing a significant number of customers each month, which is impacting both revenue and profitability. The CEO wants to understand:

Who are the customers that are churning?
What are the most influential factors contributing to churn?
How can the company proactively predict and prevent churn?

## 🛠️ My Role

In this hypothetical project, I step into the shoes of a data consultant tasked with analyzing customer churn and delivering insights that could inform strategic decisions. My objectives include:

Conducting exploratory data analysis (EDA) on customer demographics and behavior
Building a predictive model to identify customers at high risk of churning
Extracting actionable insights that could help the company reduce churn and retain valuable customers


## 📂 Dataset
The dataset contains customer details, service usage patterns, and churn labels. Key features include:
- **Customer Demographics**
- **Subscription Plans**
- **Service Usage Metrics** (Call Minutes, Data Usage, Billing)
- **Customer Service Interactions**
- **Churn Status (Target Variable)**

---

## 🛠 Feature Engineering
To improve model performance, the following transformations are applied:
- **Derived Features:**  
  - Creating new variables such as **"Average Monthly Usage"** and **"Customer Lifetime Value"**.
- **Encoding Categorical Features:**  
  - **One-Hot Encoding** for non-numeric variables to make them machine-learning friendly.
- **Handling Missing Data:**  
  - Imputing missing values using **mean/median imputation** and domain-specific assumptions.
- **Feature Scaling:**  
  -**StandardScaler** for numerical variables to normalize data.

---

## 🤖 Machine Learning Models & Evaluation

### 📌 **Planned Approach:**
The following models will be tested and evaluated based on **accuracy, precision, recall, and F1-score**:
1. **Baseline Model - Logistic Regression:**  
   - Simple, interpretable, good for understanding key churn factors.
2. **Decision Tree Classifier:**  
   - Captures non-linear relationships but prone to overfitting.
3. **Random Forest & Gradient Boosting:**  
   - More advanced ensemble methods to improve performance.
4. **Deep Learning Model (Optional):**  
   - Exploring a Neural Network approach for better prediction.

🔎 **Planned Model Evaluation:**  
- **Confusion Matrix Analysis**: To assess false positives and false negatives.  
- **ROC-AUC Score**: To compare models based on classification performance.  
- **Feature Importance Analysis**: To identify key drivers of churn.

---

## 📊 Key Findings & Business Recommendations

### 🔎 **(In Progress) Findings:**
- Identifying **customer segments** with high churn risk.
- Understanding the impact of **billing issues, customer support interactions, and subscription plans** on churn.
- Exploring **seasonal patterns** or **usage-based churn behavior**.

### 📈 **(In Progress) Recommendations:**
✅ **Enhance Customer Support**: Proactive outreach to customers with frequent complaints.  
✅ **Personalized Retention Offers**: Discounts or loyalty programs for high-risk customers.  
✅ **Improve Billing Transparency**: Reduce churn caused by confusion over charges.  
✅ **Optimize Pricing Strategies**: Offer flexible plans based on customer behavior.

---

## 📦 Dependencies
Ensure the following libraries are installed before running the analysis:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```
---
## Authur 
Matthew Huynh
