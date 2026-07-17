# 🛍️ Customer Shopping Behavior Analysis

> An end-to-end Data Analytics project that analyzes customer shopping behavior using **Python, PostgreSQL, SQL, and Power BI** to uncover purchasing trends, customer segments, and business insights.

---

# 📊 Dashboard Preview

> 📌 Add a screenshot of your Power BI dashboard here.

<p align="center">
  <img src="assets/dashboard.png" width="900">
</p>

---

# 📌 About the Project

This project focuses on analyzing customer shopping behavior using transactional data from a retail company. The objective is to understand customer purchasing patterns, product preferences, subscription behavior, and factors that influence buying decisions.

The project follows a complete data analytics workflow, including data cleaning in Python, SQL analysis using PostgreSQL, and dashboard creation in Power BI to generate meaningful business insights.

---

# 🎯 Business Problem

A retail company wants to understand its customers' shopping behavior to improve sales, customer satisfaction, and long-term loyalty.

The main goal of this project is to answer the following question:

> **"How can the company use customer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?"**

---

# 🎯 Project Objectives

- Clean and prepare the raw dataset using Python
- Perform Exploratory Data Analysis (EDA)
- Store the cleaned data in PostgreSQL
- Write SQL queries to answer business questions
- Build an interactive Power BI dashboard
- Generate business insights and recommendations

---

# 📂 Dataset Information

The dataset contains **3,900 customer purchase records** with **18 columns**, including:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Previous Purchases
- Payment Method
- Frequency of Purchases

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Data Cleaning & Analysis |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| PostgreSQL | Database |
| SQL | Business Queries |
| Power BI | Dashboard Creation |
| Jupyter Notebook | Python Development |

---

# 🔄 Project Workflow

```text
             Customer Shopping Dataset (.csv)
                         │
                         ▼
                 Python (Pandas)
                         │
                         ▼
            Data Cleaning & Preprocessing
                         │
                         ▼
         Exploratory Data Analysis (EDA)
                         │
                         ▼
               PostgreSQL Database
                         │
                         ▼
                  SQL Analysis
                         │
                         ▼
              Power BI Dashboard
                         │
                         ▼
              Business Insights
```

---

# 📁 Project Structure

```text
📁 Customer-Shopping-Behavior-Analysis
│
├── 📂 Data
│     └── customer_shopping_behavior.csv
│
├── 📂 Notebook
│     └── shopping_analysis.ipynb
│
├── 📂 SQL
│     └── customer_behaviour.sql
│
├── 📂 Dashboard
│     └── customer_behavior_dashboard.pbix
│
├── 📂 Report
│     └── Customer Shopping Behavior Analysis.pdf
│
├── 📂 Presentation
│     └── Customer-Shopping-Behavior-Analysis.pptx
│
├── 📂 Assets
│     └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

# 🧹 Data Cleaning & Preprocessing

The dataset was cleaned and prepared using Python.

The preprocessing steps included:

- Loading the dataset using Pandas
- Exploring the dataset using `info()` and `describe()`
- Handling missing values in the Review Rating column
- Renaming columns using snake_case format
- Creating new features such as Age Group
- Checking data consistency
- Preparing the dataset for SQL analysis

---

# 📊 Exploratory Data Analysis (EDA)

Exploratory analysis was performed to understand customer shopping behavior.

Some of the analysis included:

- Purchase Amount Distribution
- Customer Age Distribution
- Gender-wise Analysis
- Category-wise Sales
- Subscription Analysis
- Review Rating Distribution
- Discount Analysis
- Seasonal Purchase Trends

---

# 🗄️ SQL Analysis

The cleaned dataset was imported into PostgreSQL, where SQL queries were written to answer business questions.

The analysis included:

- Revenue by Gender
- High-Spending Discount Users
- Top Rated Products
- Shipping Type Comparison
- Subscribers vs Non-Subscribers
- Discount-Dependent Products
- Customer Segmentation
- Top Products by Category
- Repeat Buyers Analysis
- Revenue by Age Group

---

# 📈 Power BI Dashboard

The interactive dashboard provides insights into customer shopping behavior.

Dashboard includes:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Subscription Status Analysis
- Interactive Filters

---

# 💡 Key Insights

Some important insights obtained from the analysis:

- Female customers generated slightly higher revenue than male customers.
- Express shipping customers spent more on average than standard shipping customers.
- Subscribers showed better purchasing behavior than non-subsscribers.
- Loyal customers formed the largest customer segment.
- Some products were purchased with discounts much more frequently than others.
- Young adults contributed the highest revenue among all age groups.

---

# 🚀 Skills Learned

Through this project, I learned:

- Data Cleaning
- Exploratory Data Analysis
- Python Programming
- Pandas
- PostgreSQL
- SQL Query Writing
- Data Visualization
- Dashboard Development
- Business Insight Generation

---

# ▶️ How to Run the Project

### Clone the repository

```bash
git clone https://github.com/yourusername/Customer-Shopping-Behavior-Analysis.git
```

### Install required libraries

```bash
pip install pandas numpy matplotlib sqlalchemy psycopg2
```

### Run the project

1. Open the Jupyter Notebook.
2. Run all Python cells.
3. Import the cleaned data into PostgreSQL.
4. Execute the SQL queries.
5. Open the Power BI dashboard.
6. Explore the dashboard and insights.

---

# 📈 Future Improvements

- Build customer segmentation using Machine Learning
- Predict customer purchasing behavior
- Create an online interactive dashboard
- Automate data loading using Python

---

# 👨‍💻 Author

**R. Akshith Reddy**

B.Tech Chemical Engineering  
National Institute of Technology Warangal

### Skills

Python • SQL • PostgreSQL • Power BI • Pandas • Data Analysis • Data Visualization


