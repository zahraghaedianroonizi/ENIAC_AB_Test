# 📊 ENIAC A/B Test Project

## 🎯 Project Overview

This project analyzes an A/B test experiment for ENIAC to identify which call-to-action (CTA) button design performs best.

The purpose of the experiment is to understand how visual design elements such as button color and button text influence user behavior and click performance.

Four button variants were included in the experiment:

🅰️ Version A → White **"SHOP NOW"**  
🅱️ Version B → Red **"SHOP NOW"**  
🅲️ Version C → White **"SEE DEALS"**  
🅳️ Version D → Red **"SEE DEALS"**

The analysis combines experimental design thinking, statistical testing, and business interpretation to support data-driven decision making.

---

## 💼 Business Problem

ENIAC aims to optimize user interaction and improve engagement with its website.

The company wants to understand:

✅ Which CTA button design performs best  
✅ Whether color impacts user behavior  
✅ Whether button text affects engagement  
✅ Which variation should be implemented

The experiment helps identify the highest-performing version using real user interaction data.

---

## 🚀 Business Value

Improving click-through rate (CTR) can lead to:

📈 Higher user engagement  
💡 Better interaction with products  
💰 Increased conversion opportunities  
📊 Stronger business decisions based on data

Even small improvements in user interaction can generate measurable business impact.

---

## 🗂️ Dataset Description

The dataset contains tracking information collected during an online A/B test.

Several elements were tracked; therefore, only the main CTA buttons relevant to the experiment were extracted and analyzed.

### Variants analyzed:

| Version | Button Color | Button Text |
|----------|--------------|--------------|
| A | White | SHOP NOW |
| B | Red | SHOP NOW |
| C | White | SEE DEALS |
| D | Red | SEE DEALS |

---

## ⚙️ Project Workflow

### 1️⃣ Experimental Design

The experiment included all four variants because two independent variables were tested simultaneously:

🎨 Button color  
📝 Button text

Questions addressed:

- Should all variants be included?
- What is the business value?
- Which metric should be selected?

---

### 2️⃣ Data Preparation

Steps:

📂 Load CSV files  
🧹 Extract click information  
🔎 Filter main CTA buttons  
📋 Prepare data for analysis

Libraries used:

- Pandas
- NumPy

---

### 3️⃣ Metric Selection

## 📌 Primary Metric: Click Through Rate (CTR)

CTR measures:

CTR = Number of Clicks / Number of Visits

CTR was selected because it directly reflects user engagement with CTA buttons.

---

## 📉 Statistical Analysis

To determine whether differences between versions were statistically significant, a Chi-Square Test was applied.

Analysis included:

📊 Relationship between button variation and clicks  
📈 Statistical significance  
🧪 Experimental comparison

Libraries:

- SciPy
- NumPy

---

## 🛠️ Tools Used

🐍 Python  
🐼 Pandas  
🔢 NumPy  
📈 SciPy  
🎨 Seaborn  
☁️ Google Colab  
💻 GitHub

---

## 📁 Project Structure

```text
ENIAC_AB_Test/
│
├── Copy_of_ENIAC_AB_Test.ipynb
├── Data/
│   ├── eniac_a.csv
│   ├── eniac_b.csv
│   ├── eniac_c.csv
│   └── eniac_d.csv
│
└── README.md
```

---

## ✨ Key Insights

This project demonstrates practical experience with:

✅ A/B testing methodology  
✅ Experimental design  
✅ Statistical hypothesis testing  
✅ Data analysis  
✅ Business interpretation  
✅ Data-driven decision making

---

## 🔮 Future Improvements

Potential future enhancements:

📊 Additional visualizations  
📏 Confidence interval analysis  
🧪 Further statistical testing  
📈 Interactive Tableau dashboards

---

## 👩‍💻 Author

**Zahra Ghaedianroonizi**

🎓 M.Sc. in Mathematical Statistics  
📚 Data Analytics Training  
💡 SQL | Python | Tableau

