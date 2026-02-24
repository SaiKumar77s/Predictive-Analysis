# 📊 Predictive Analysis 

---

## 🎯 Project Objective

The objective of this project is to build a Machine Learning Classification Model to predict whether a customer order will be **Delivered or Cancelled** based on historical sales data.

This predictive system helps the business to:

- Reduce order cancellations  
- Improve delivery success rate  
- Identify high-risk transactions  
- Make data-driven decisions  
- Increase future sales performance  

---

## 📂 Dataset Information


## Dataset used
- <a href="https://github.com/SaiKumar77s/Predictive-Analysis/blob/main/advertising.csv">Dataset</a>



The dataset contains:

- Customer demographics  
- Product category  
- Order amount  
- Sales channel  
- State / Region  
- Order status (Target Variable)  

### Target Variable:
`Order_Status`

---

## ❓ Business Problem

Build a Classification Model to predict:

> Whether an order will be Delivered or Cancelled.

---

## 🛠️ Project Workflow

### 1️⃣ Data Preprocessing
- Checked missing values  
- Removed null records  
- Verified data types  
- Cleaned inconsistent values  

### 2️⃣ Feature Engineering
Selected important features:

- Gender  
- Age  
- State  
- Category  
- Channel  
- Order Amount  
- Month  

### 3️⃣ Model Building
Implemented the following algorithms:

- Logistic Regression  
- Decision Tree  
- Random Forest Classifier  

### 4️⃣ Model Evaluation
Evaluation metrics used:

- Accuracy Score  
- Confusion Matrix  
- Precision  
- Recall  
- F1 Score  

---

## 📁 Project Structure

``'
predictive-analysis-ml/
│
├── data/
│   └── sales_data.csv
│
├── notebook/
│   └── predictive_analysis.ipynb
│
├── src/
│   └── model.py
│
├── requirements.txt
└── README.md
```




```

## 📊 Key Insights

- Customers aged 30–49 have higher successful delivery rates  
- Certain states show higher cancellation probability  
- Order amount influences order status  
- Sales channel plays a significant role in delivery success  



## ✅ Final Conclusion

By implementing a Machine Learning model, the business can:

- Predict risky orders before confirmation  
- Reduce losses from cancellations  
- Improve operational efficiency  
- Create data-driven marketing strategies  

This project demonstrates real-world application of Machine Learning in Retail Analytics.

---

## 🔮 Future Improvements

- Hyperparameter tuning (GridSearchCV)  
- Model comparison with XGBoost  
- Deployment using Streamlit  
- Add Time Series Sales Forecasting  



