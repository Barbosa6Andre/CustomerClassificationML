# Customer Segmentation MVP Using Unsupervised Machine Learning  
**MVP (Minimum Viable Product) for customer segmentation using unsupervised machine learning techniques.**  
This project explores purchasing behavior patterns in a retail context through clustering methods like **K-Means** and **DBSCAN**, delivering data-driven insights for business strategy and customer engagement.

---

## 📘 Google Colab Notebook  
Access the full notebook here:  
https://colab.research.google.com/drive/1M5M-65vafguW5Kn283dJeRM2f2a44yQL?usp=sharing

---

## 🧠 Problem Definition  
The goal of this project is to uncover actionable insights from customer transaction behavior to:

1. Identify distinct customer segments  
2. Support targeted marketing and personalized strategies  
3. Improve resource allocation and customer retention

This is approached using **unsupervised learning**, allowing clusters to emerge directly from the data.

---

### ❓ Key Questions  
- Can we segment customers into meaningful groups using transactional data?  
- How do different segments contribute to the business?  
- What strategies can be applied for engagement and retention?

---

## 🚀 Why This MVP Matters  
This MVP demonstrates the power of **machine learning segmentation** by:

- Applying a **scalable, data-driven framework**  
- Highlighting behavioral patterns without human-imposed bias  
- Offering real-world strategic recommendations for customer satisfaction and lifetime value

The project shows how raw data can translate into **practical decisions**.

---

## 📊 Notebook Structure  

0. **Preparing the Environment**  
   Set up Python libraries and environment configurations.

1. **Handling Missing Values, Duplicates, Wrong Value Types, and Outliers**  
   Ensure consistency and reliability through data cleaning.

2. **Feature Engineering and RFM Segmentation**  
   Create Recency, Frequency, and Monetary (RFM) metrics to quantify customer behavior.

3. **Data Preprocessing and Classification Algorithms**  
   Scale RFM values and prepare data for clustering using **K-Means** and **DBSCAN**.

4. **Customer Segmentation with Machine Learning**  
   Apply clustering and visualize group patterns.

5. **Conclusion**  
   Summarize findings and value of ML segmentation.

6. **Recommendations**  
   Propose actionable business strategies based on cluster profiles.

---

## 📦 Dataset Details  

- **Name**: Online Retail Transaction Data  
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/thedevastator/online-retail-transaction-data/data)  
- **Domain**: UK-based e-commerce store selling unique all-occasion gifts  

### 📋 Attributes:
- `InvoiceNo`: Unique 6-digit transaction ID (prefix "C" = cancellation)  
- `StockCode`: 5-digit product identifier  
- `Description`: Product name  
- `Quantity`: Number of items per transaction  
- `InvoiceDate`: Timestamp of transaction  
- `UnitPrice`: Price per unit  
- `CustomerID`: Unique customer ID  
- `Country`: Country of customer

---

## ⚙️ How to Use This Repository  

1. Open the notebook in **Google Colab** using the following link: https://colab.research.google.com/drive/1M5M-65vafguW5Kn283dJeRM2f2a44yQL?usp=sharing
2. Follow the step-by-step sections from data cleaning to clustering  
3. Review the **recommendations per cluster** to understand strategic applications

---

## ✅ Final Thoughts  
This project demonstrates how unsupervised ML techniques like clustering can reveal hidden behavior patterns and support marketing, operations, and personalization strategies. By letting the **data speak for itself**, businesses can move toward **more intelligent, targeted decision-making**.
