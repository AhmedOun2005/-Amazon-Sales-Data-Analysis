# 🛒 Amazon Sales Data Analysis & Dashboard

## 📌 Overview
This project analyzes Amazon sales data to uncover business insights related to sales performance, customer behavior, fulfillment operations, and regional trends.

The project combines:
- Data Analysis using Python
- Exploratory Data Analysis (EDA)
- Business Intelligence & Visualization
- Interactive Dashboarding using Power BI

---

## 🎯 Objectives
- Analyze sales performance across categories and states
- Identify top-performing products and regions
- Explore shipping and fulfillment operations
- Understand customer purchasing behavior
- Build an interactive dashboard for business insights

---

# 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- Jupyter Notebook

---

# 📂 Dataset Features

| Feature | Description |
|---|---|
| Order ID | Unique order identifier |
| Date | Transaction date |
| Category | Product category |
| Amount | Sales amount |
| Qty | Quantity sold |
| ship-state | Shipping state |
| Fulfilment | Amazon / Merchant |
| Courier Status | Shipping status |
| Sales Channel | Amazon / Non-Amazon |
| B2B | Business-to-business order |

---

# 🧹 Data Preprocessing
The following preprocessing steps were performed:

- Handling missing values
- Removing duplicates
- Formatting date columns
- Data type conversion
- Feature engineering
- Aggregation and grouping

---

# 📊 Exploratory Data Analysis (EDA)

## 🔹 Sales Analysis
- Total Sales Amount
- Average Order Value
- Monthly Sales Trends
- Quarterly Revenue Analysis

## 🔹 Product Analysis
- Sales by Category
- Sales by Product Size
- Top-Selling Categories

## 🔹 Shipping & Fulfillment Analysis
- Courier Status Distribution
- Fulfillment Performance
- Amazon vs Merchant Fulfillment

## 🔹 Geographic Analysis
- State-wise Sales Analysis
- Regional Revenue Distribution

---

# 📈 Dashboard Features

The interactive Power BI dashboard includes:

- KPI Cards
- Bar Charts
- Donut Charts
- Pie Charts
- Trend Analysis
- Category Comparisons
- Regional Sales Analysis
- Fulfillment Insights

---

# 📷 Dashboard Preview

<img width="100%" alt="Amazon Dashboard" src="dashboard.png">

---

# 📌 Key Insights
- Set category generated the highest revenue.
- Most orders were successfully shipped.
- Amazon fulfillment handled the majority of orders.
- Maharashtra contributed the highest sales amount.
- Strong sales trends were observed across specific categories and regions.

---

# 🚀 Project Structure

```bash
📁 Amazon-Sales-Analysis
│
├── analysis.ipynb (note Book for EDA)
├── Amazon.pbix (Power Bi Dashboard)
├── README.md 
└── Amazon_Sales.csv 
└── final_Amazon_set.csv (Final ds after EDA for Visualization)
└── Questions.ipynb (Business Questions for building good dashboard)
```

---

# ▶️ How to Run

## 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/amazon-sales-analysis.git
```

## 2️⃣ Install Required Libraries
```bash
pip install pandas numpy matplotlib seaborn
```

## 3️⃣ Run Jupyter Notebook
```bash
jupyter notebook
```

Open:
```bash
analysis.ipynb
```

---

# 👨‍💻 Author
Ahmed Oun

---

# ⭐ Future Improvements
- Sales Forecasting Models
- Customer Segmentation
- Recommendation Systems
- Real-time Dashboard Integration
- Advanced Predictive Analytics

---

# 📜 License
This project is for educational and portfolio purposes.
