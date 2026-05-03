---

# 📊 Olist E-Commerce Customer Behavior Analysis

## 🔍 Overview

This project analyzes the **Olist Brazilian E-Commerce dataset (2016–2018)** to uncover actionable insights on customer behavior, delivery performance, and revenue drivers.

The objective is to transform raw transactional data into **data-driven business recommendations** that improve:

* Customer retention
* Delivery efficiency
* Revenue growth

---

## 🎯 Key Metrics

* 📦 Total Orders: ~99K
* 💰 Total Revenue: R$16M
* 👥 Unique Customers: ~96K
* 🔁 Repeat Purchase Rate: **~3% (very low)**
* ⭐ Avg Review Score: 4.08
* 🚚 Late Deliveries: **~20.7%**

---

## 📈 Key Insights

### 🚚 Delivery Performance is Critical

* Late deliveries significantly reduce customer satisfaction
* Strong statistical evidence (p < 0.001)
* Major driver of negative reviews

---

### 🔁 Weak Customer Retention

* Only ~3% repeat customers
* Sharp drop-off after first purchase
* Indicates missing retention strategy

---

### ⏰ Customer Purchase Behavior

* Peak ordering time: **10 AM – 4 PM**
* Higher spending on weekends
* Suggests intentional (non-impulsive) buying behavior

---

### 🛍️ Product Category Trends

Top revenue categories:

* Bed & Bath
* Health & Beauty
* Sports & Leisure

⚠️ High revenue does not always mean high satisfaction

---

### 💳 Payment Behavior

* ~75% transactions via credit card
* Higher order values vs other methods
* Strong adoption of installment-based purchasing

---

## 🧪 Hypothesis Testing

### H1: Late deliveries reduce review scores

* ✅ Confirmed
* Test: Mann-Whitney U
* p-value < 0.001
* Large effect size

---

### H2: Product price influences satisfaction

* ✅ Confirmed
* Test: Kruskal-Wallis
* p-value < 0.05
* Mid-to-high priced items perform better

---

## 🚀 Business Recommendations

### 1. Delivery Optimization (High Priority)

* ML-based delivery time prediction
* Target ≥90% on-time delivery
* Proactive compensation for delays

---

### 2. Smart Marketing Strategy

* Run campaigns between **10 AM – 2 PM**
* Launch “Lunch Break Deals”
* Weekend bundle promotions

---

### 3. Retention Engine

* Post-purchase engagement flows
* Personalized recommendations
* Incentivize second purchase

---

## 🔮 Further Exploration

* Impact of first delivery experience on long-term retention (LTV)
* Cohort-based survival analysis
* Logistics route optimization
* Extended dataset for trend validation

---

## 📂 Dataset

This project uses the Olist dataset from Kaggle:

👉 [https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Due to file size limitations, the dataset is **not included** in this repository.

---

## 📁 How to Run This Project

### 1. Download Dataset

Download from Kaggle and extract into a `data/` folder.

### 2. Expected Structure

```id="struct1"
project/
├── data/
│   ├── orders.csv
│   ├── customers.csv
│   ├── order_items.csv
│   └── ...
├── notebook/
│   └── Olist_EDA_HabuilCaseStudy.ipynb
├── report/
│   └── Olist_Data_Analysis_Report.pdf
└── README.md
```

### 3. Run Notebook

Open and run:

```
notebook/Olist_EDA_HabuilCaseStudy.ipynb
```

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* SciPy (statistical testing)

---

## 🤖 LLM Usage Disclosure

**Models Used:**

* ChatGPT (GPT-5.3)
* Claude (Anthropic Sonnet)

### Used For:

* Code syntax suggestions
* Statistical test templates
* Visualization improvements
* Report structuring

### Not Used For:

* Core analysis execution
* Business insights
* Final conclusions

All analysis and insights were independently validated.

---

## 📎 Notebook

👉 [https://github.com/your-username/olist-ecommerce-customer-behavior-analysis](https://github.com/your-username/olist-ecommerce-customer-behavior-analysis)

---

## 👤 Author

**Hasini**

* 🎓 Data Science Student
* 💼 Aspiring Data Analyst / Data Scientist
* 🔗 LinkedIn: [https://www.linkedin.com/in/hasini-p-694357261/](https://www.linkedin.com/in/hasini-p-694357261/)

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐

---


