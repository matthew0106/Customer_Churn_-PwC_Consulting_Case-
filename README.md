# 📊 PwC Churn Analysis Project

![image](https://github.com/user-attachments/assets/e3981a05-5db8-4828-8f36-7efd8ec6922c)

## 📌 Overview
This project aims to analyse **customer churn patterns** in the PwC dataset to identify key drivers of churn and develop predictive models to enhance customer retention. By understanding the characteristics of **churned vs. retained customers**, this analysis will help businesses implement **targeted strategies** to reduce churn and improve customer experience.

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

## Authur
Matthew Huynh
