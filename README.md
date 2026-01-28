# Olist E-Commerce Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs an end-to-end Exploratory Data Analysis (EDA) on the **Olist Brazilian E-Commerce Dataset** to understand customer behavior, order trends, delivery performance, payment patterns, seller efficiency, and customer satisfaction. The goal is to derive actionable business insights that can help improve logistics, marketplace operations, and customer experience.

---

## 🎯 Objectives

* Analyze order and sales trends over time
* Evaluate delivery performance and identify delays
* Study customer payment behavior and installment patterns
* Assess seller performance and freight costs
* Understand factors affecting customer reviews and satisfaction

---

## 🗂 Dataset Description

The analysis uses a **merged dataset** created from multiple Olist datasets, including:

* Orders
* Customers
* Payments
* Order Items
* Sellers
* Reviews

Feature engineering was performed to create additional variables such as delivery time, delay flag, and monthly trends.

---

## 🛠 Tools & Technologies

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook
* **Version Control:** Git & GitHub

---

## 📊 Key Analyses Performed

### ✔ Univariate Analysis

* Order amount distribution
* Order status distribution
* Payment installments usage
* Review score distribution

### ✔ Bivariate Analysis

* Order amount vs customer state
* Delivery time vs review score
* Payment type vs order count
* Installments vs total order value

### ✔ Multivariate Analysis

* Correlation heatmap of key numeric variables
* Pairplot of order amount, freight, products, and reviews
* Order status comparison across states
* Monthly trends of orders, payments, and reviews

---

## 🔍 Key Insights

* Order volume shows a clear upward growth trend over time.
* Delivery delays negatively impact customer review scores.
* Credit card is the most commonly used payment method.
* A small number of states contribute to a large share of total orders.
* Higher freight charges and longer delivery times reduce customer satisfaction.

---

## 📁 Project Structure

```
├── data/
│   └── olist_merged_dataset.csv
├── notebooks/
│   └── Olist_EDA.ipynb
├── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/olist-ecommerce-eda.git
   ```
2. Install required libraries

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the Jupyter Notebook and run all cells

   ```bash
   jupyter notebook
   ```

---

## 📌 Conclusion

This EDA project provides valuable insights into Olist’s e-commerce operations, highlighting key areas such as delivery efficiency, customer satisfaction, and sales trends. The findings can support data-driven decision-making for improving marketplace performance and user experience.

---

## 👤 Author

**PURUSHOTTAM KUMAR**

---

⭐ If you find this project useful, feel free to star the repository!
