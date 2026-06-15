# 🛒 E-Commerce Customer Segmentation using RFM Analysis

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

This project performs **RFM (Recency, Frequency, Monetary) Analysis** on a real-world e-commerce dataset containing **1 million+ transactions**. The goal is to segment customers based on their buying behavior and help businesses make smarter marketing decisions.

---

## 🎯 Objective

- Identify **who are the best customers**
- Find customers who are **at risk of leaving**
- Discover **lost customers** who haven't bought in a long time
- Help businesses **target the right customers** with the right strategy

---

## 📊 What is RFM?

| Letter | Meaning | Question Asked |
|--------|---------|----------------|
| **R** — Recency | How recently did the customer buy? | Days since last purchase |
| **F** — Frequency | How often do they buy? | Total number of orders |
| **M** — Monetary | How much do they spend? | Total amount spent |

---

## 📁 Dataset

- **Source:** Online Retail II Dataset — UCI Machine Learning Repository
- **Size:** 1,067,371 rows × 8 columns
- **Period:** December 2009 to December 2011
- **Columns:** Invoice, StockCode, Description, Quantity, InvoiceDate, Price, CustomerID, Country

---

## 🛠️ Tools & Technologies

- **Language:** Python 3.11
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook
- **Version Control:** Git & GitHub

---

## 🪜 Project Steps

```
Step 1 → Loaded dataset (1M+ rows)
Step 2 → Cleaned data (removed nulls, cancelled orders, negative values)
Step 3 → Created TotalPrice column (Quantity × Price)
Step 4 → Calculated RFM values for each customer
Step 5 → Scored customers on scale of 1-5
Step 6 → Segmented customers into 8 groups
Step 7 → Visualized results with charts
Step 8 → Saved final results to CSV
```

---

## 👥 Customer Segments

| Segment | Description | Strategy |
|---------|-------------|----------|
| 👑 Champions | Buy recently, often, and spend the most | Reward them, ask for reviews |
| ❤️ Loyal Customers | Buy regularly and spend well | Upsell higher value products |
| 🌱 New Customers | Bought recently but not often | Onboarding offers and discounts |
| 🌟 Potential Loyalists | Recent buyers with decent frequency | Loyalty programs |
| ⚠️ At Risk | Used to buy often but stopped | Send win-back emails |
| 😴 Can't Lose Them | High spenders who haven't bought recently | Aggressive discounts |
| 🔔 Needs Attention | Average customers going cold | Limited time offers |
| ❌ Lost | Haven't bought in a long time | Low priority — minimal spend |

---

## 📈 Key Insights

- **5,878 unique customers** were analyzed
- **Loyal Customers** form the largest segment (2,134 customers — 36%)
- **Champions** spend on average **5x more** than Lost customers
- **634 At Risk customers** need immediate win-back campaigns
- **756 Champions** should be rewarded with loyalty programs

---

## 📊 Visualizations

### Customer Segment Distribution (Pie Chart)
Shows the percentage of customers in each segment

### Average Revenue by Segment (Bar Chart)
Shows which customer segment generates the most revenue

---

## 📂 Project Structure

```
rfm-project/
│
├── RFM Analysis.ipynb        ← Main Jupyter Notebook
├── rfm_segments.csv          ← Final RFM results
├── segments_pie.png          ← Pie chart visualization
├── revenue_by_segment.png    ← Revenue bar chart
└── README.md                 ← Project documentation
```

---

## 🚀 How to Run This Project

1. Clone the repository:
```bash
git clone https://github.com/naushadkhan18072003-cyber/RFM-Analysis.git
```

2. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Download the dataset from Kaggle:
```
kaggle.com → search "Online Retail II UCI" → download CSV
```

4. Place CSV file in project folder and open Jupyter Notebook:
```bash
jupyter notebook
```

5. Run **RFM Analysis.ipynb** cell by cell

---

## 👨‍💻 Author

**Naushad Khan**
- 🎓 MCA Student — Cloud & DevOps Engineering
- 📍 Gurugram, India
- 🔗 GitHub: [naushadkhan18072003-cyber](https://github.com/naushadkhan18072003-cyber)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ **If you found this project helpful, please give it a star!** ⭐
