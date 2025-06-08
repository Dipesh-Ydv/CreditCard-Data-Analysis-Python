
# Credit Card Data Analysis 🧾💳

## 📘 Business Problem

To improve decision-making in the modern credit card industry, PSPD Bank aims to evaluate customer behavior using transaction data. This analysis will help the bank proactively manage risks like bankruptcy and fraud, understand customer repayment behavior, and identify opportunities for tailored offers.

Mr. Jim Watson, CEO of PSPD Bank, has initiated this study to better analyze:

- Spend patterns across demographics
- Repayment behaviors
- Profitability from interest on monthly spend

---

## 📊 Dataset Overview

The dataset comprises three sheets:

- **Customer Acquisition**: Details about the customer at the time of card issuance
- **Spend**: Transaction-level credit card spend data
- **Repayment**: Repayment records for each customer

---

## 🧹 Data Preprocessing Rules

1. If age < 18 → Replace with mean age.
2. If spend > card limit → Replace with 50% of the limit.
3. If repayment > card limit → Replace with the card limit.

---

## 📈 Analysis Tasks

### 🔢 Summaries to Extract

- Total number of unique customers
- Total number of distinct product categories
- Average monthly spend per customer
- Average monthly repayment per customer
- Monthly profit calculation based on 2.9% interest rate

### 💡 Insights to Generate

- Top 5 product types
- City with highest total spend
- Age group spending the most
- Top 10 customers based on total repayment

### 📍 City-Wise Analysis

- Annual spend per product by city with graphical representation

---

## 📉 Graphs to Visualize

- Monthly spend comparison, city-wise
- Yearly spend on air tickets
- Monthly product spend trends (for seasonality detection)

---

## 🔁 Custom Python Function

A dynamic function is implemented to identify **top 10 customers per city**, based on:

- Selected **product type** (Gold/Silver/Platinum)
- **Time frame** (monthly/yearly)

This function allows flexible querying for targeted marketing and performance tracking.

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **IDE**: Jupyter Notebook / VS Code

---

## 📁 Project Structure

```plaintext
credit-card-analysis/
│
├── data/
│   └── credit_card_data.xlsx
│
├── notebooks/
│   └── Credit_Card_Analysis.ipynb
│
├── graphs/
│   └── monthly_product_spend.png
│   └── monthly_spend_city_wise.png
│   └── yearly_air_ticket_spend.png
│   └── yearly_total_spend_by_city_stacked_by_product.png
│   └── yearly_total_spend_by_product_stacked_by_cities.png
│
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-analysis.git
   cd credit-card-analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open and run the notebook:
   ```bash
   jupyter notebook notebooks/Credit_Card_Analysis.ipynb
   ```

---

## 📌 Key Outcomes

- Clear visibility into customer behavior
- Identification of high-value customers and cities
- Improved fraud detection through limit analysis
- Enhanced profitability tracking for PSPD Bank

---

## 📞 Contact

For queries, reach out at: [dipeshyadav4444@gmail.com]

