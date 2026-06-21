# 🛒 Superstore Sales Analysis & Demand Forecasting

A complete data analysis and machine learning project on the Sample Superstore retail dataset.
Covers exploratory data analysis, business insights, and a Random Forest demand forecasting model.

---

## 📌 Project Overview

Retail businesses need to understand **which products sell, which regions profit, and how to forecast demand**.
This project analyses a real-world superstore dataset to answer those questions using Python — and builds
a predictive ML model to forecast product quantity demand.

---

## 📊 What This Project Does

### 🔍 Exploratory Data Analysis (EDA)
- Sales summary statistics (total, average, max, min)
- Category and sub-category order distribution
- Region-wise and segment-wise breakdowns
- Profit/loss labelling per order

### 📈 Business Analytics
| Analysis | Description |
|---|---|
| Sales Performance Labels | Classifies orders as High / Medium / Low sales |
| Top Selling Analysis | Top categories, cities, and regions by revenue |
| Profit Margin Analytics | Calculates margin % per order |
| Category Contribution % | Each category's share of total sales |
| Loss-Making Products | Sub-categories with negative total profit |
| Discount Danger Zone | How discount levels affect average profit |
| Category Profitability Matrix | Sales vs Profit vs Discount per category |
| Region Risk Profile | Flags regions with net losses |
| Bulk Order Analytics | Identifies high-quantity orders |
| City-Level Diagnostic | Top 10 loss-making cities |

### 🤖 Machine Learning — Demand Forecasting
- **Model:** Random Forest Regressor
- **Target:** Product Quantity demanded
- **Features:** Sales, Discount, Profit, Ship Mode, Segment, Region, Category, Sub-Category
- **Preprocessing:** Label Encoding for categorical variables
- **Evaluation Metrics:** RMSE, MAE, R² Score, Feature Importance

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Scikit-learn | ML model & preprocessing |
| Jupyter Notebook | Development environment |

---

## 📁 Project Structure

```
superstore-analysis/
│
├── superstore_.ipynb       # Main notebook (EDA + ML)
├── Superstore.csv          # Dataset (place here before running)
└── README.md               # Project documentation
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/superstore-analysis.git
   cd superstore-analysis
   ```

2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

3. Add the dataset file `Superstore.csv` to the project folder.

4. Open the notebook:
   ```bash
   jupyter notebook superstore_.ipynb
   ```

5. Run all cells from top to bottom (`Cell → Run All`).

---

## 📌 Key Results

- Identified **Technology** as the highest revenue-generating category
- Found that **high discounts (>30%) consistently lead to negative profit**
- Random Forest model achieved strong demand prediction performance
- **West region** recorded the highest total sales; certain cities flagged as high-loss zones

---

## 📂 Dataset

**Sample Superstore** — a widely used retail dataset containing ~10,000 orders across the US.

Columns include: `Order ID`, `Order Date`, `Ship Mode`, `Segment`, `Region`, `Category`,
`Sub-Category`, `Sales`, `Quantity`, `Discount`, `Profit`

> Dataset source: [Kaggle - Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

---

## 👤 Author

**Kiran Chaudhary**
Python Developer | Data Analyst | ML/AI Developer
📧 kirtichaudhary1221@gmail.com
🔗 [GitHub](https://github.com/your-username)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
