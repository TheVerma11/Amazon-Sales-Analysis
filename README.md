# Amazon Sales Analysis

## 📌 Project Overview

This project performs an exploratory analysis of Amazon sales data to understand
sales performance, product performance, customer behavior, payment methods,
branch performance, and customer ratings.

The analysis uses Python, Pandas, SQL concepts, and data visualization
techniques to answer 28 business-related questions and generate actionable
insights.

---

## 🎯 Objectives

- Analyze sales and revenue performance
- Identify high-performing product lines
- Understand customer purchasing behavior
- Analyze payment method preferences
- Compare branch and city performance
- Analyze customer ratings
- Identify sales trends by month, day, and time of day
- Generate business insights from the data

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- MySQL Workbench
- PyMySQL
- SQLAlchemy
- Jupyter Notebook

---

## 📂 Dataset

The project uses an Amazon sales dataset containing information related to:

- Branch
- City
- Customer Type
- Gender
- Product Line
- Unit Price
- Quantity
- Tax / VAT
- Total
- Date
- Time
- Payment Method
- Cost of Goods Sold (COGS)
- Gross Income
- Customer Rating

---

## 🔄 Data Analysis Workflow

### 1. Data Wrangling

The project includes:

- Database schema creation
- Data loading
- Database connectivity
- Data validation
- Missing-value checking

MySQL Workbench was used as part of the database workflow, while
PyMySQL and SQLAlchemy were used for database-related operations.

### 2. Feature Engineering

Additional features were created from the existing date and time information:

- `timeofday`
- `dayname`
- `monthname`
- `hour`

These features were used for time-based sales and customer-rating analysis.

### 3. Exploratory Data Analysis

The analysis investigates product, sales, customer, branch,
payment, and rating patterns.

A total of **28 business questions** were explored.

---

## 📊 Key Business Questions

Some of the questions investigated include:

1. How many distinct cities are present?
2. Which city corresponds to each branch?
3. How many product lines are present?
4. Which payment method is most frequently used?
5. Which product line has the highest sales?
6. How much revenue is generated each month?
7. When does COGS reach its peak?
8. Which product line generates the highest revenue?
9. Which city records the highest revenue?
10. Which product line incurs the highest VAT?
11. Which product lines perform above average?
12. Which branch exceeds the average number of products sold?
13. Which product lines are associated with each gender?
14. What is the average rating for each product line?
15. When do customers provide the most ratings?
16. Which customer type contributes the highest revenue?
17. Which city has the highest VAT percentage?
18. Which customer type pays the highest VAT?
19. How many customer types are present?
20. How many payment methods are present?
21. Which customer type occurs most frequently?
22. Which customer type has the highest purchase frequency?
23. What is the predominant customer gender?
24. How is gender distributed across branches?
25. When do customers provide the most ratings?
26. What is the highest-rated time of day for each branch?
27. Which day has the highest average rating?
28. Which day has the highest average rating for each branch?

---

## 🔍 Key Insights

### Product Analysis

- There are **6 distinct product lines**.
- **Food and beverages** recorded the highest sales value.
- Sales performance was categorized into "Good" and "Bad" based on
  comparison with average sales.

### Sales Analysis

- **Ewallet** is the most frequently used payment method.
- The highest revenue was recorded in **January 2019**.
- The highest COGS was also recorded in **January 2019**.
- **Naypyitaw** recorded the highest revenue among the cities.
- **Food and beverages** incurred the highest VAT.

### Customer Analysis

- **Members** contributed the highest revenue.
- Female customers slightly outnumber male customers.
- Customer ratings are most frequent during the **afternoon**.
- Branch-specific rating patterns vary by time of day.

---

## 💡 Business Recommendations

Based on the analysis, the project identifies several areas for improvement:

- Diversify and improve underperforming product lines.
- Optimize preferred payment methods and promotions.
- Investigate factors contributing to high COGS.
- Improve branch-level performance using localized strategies.
- Strengthen customer engagement through personalized marketing.
- Introduce and improve loyalty programs to encourage repeat purchases.

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/TheVerma11/Amazon-Sales-Analysis.git