# 📊 Customer Churn Analysis and Predictive Modeling

## 📌 Overview
This project analyzes customer churn patterns and builds a predictive model to identify customers likely to leave the company.

---

## 🔍 Key Insights

- **Overall Churn Rate: 26.5%**
- New customers (low tenure) churn more.
- Month-to-month contract customers have the highest churn.
- Customers with higher monthly charges are more likely to churn.
- Customers without dependents and partner churn more.
- Lack of tech support and online security increases churn.
- Customers using electronic check payment method churn more.

---

## 🤖 Predictive Modeling

**Model Used:** Logistic Regression  

**Initial Model Performance:**
- Recall (Churn): 0.47  
- F1 Score: 0.52  

**After Handling Class Imbalance (`class_weight='balanced'`):**
- Accuracy score: 0.74
- Recall (Churn): 0.79  
- F1 Score: 0.62
  
The improvement significantly increased the model’s ability to detect at-risk customers.

---
## VISUALIZATION

<img width="831" height="709" alt="Screenshot 2026-02-18 185813" src="https://github.com/user-attachments/assets/71ea4390-c3a2-4537-ad45-9ddeb2e27a85" />

<img width="849" height="746" alt="Screenshot 2026-02-18 185832" src="https://github.com/user-attachments/assets/869e9605-94e9-416a-a86f-ac48891866aa" />

<img width="1268" height="664" alt="Screenshot 2026-02-18 185938" src="https://github.com/user-attachments/assets/ee6c55fc-e861-4765-bb2f-789fc3702748" />


---
## 🛠 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 💡 Conclusion

This project demonstrates how data analysis and predictive modeling can help businesses identify high-risk customers and design targeted retention strategies.
