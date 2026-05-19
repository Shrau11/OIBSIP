# Exploratory Data Analysis (EDA) on Retail Sales Data

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a retail sales dataset to understand customer behavior, sales trends, and product performance. The analysis helps uncover meaningful business insights that can support data-driven decision-making for retail businesses.

---

## Dataset Information
The dataset contains retail transaction details including:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

---

## Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

---

## Project Workflow

### 1. Data Loading and Cleaning
- Loaded the retail sales dataset
- Checked dataset structure and data types
- Verified missing values
- Removed duplicate records

### 2. Descriptive Statistics
- Analyzed statistical measures such as:
  - Mean
  - Median
  - Standard Deviation
  - Minimum and Maximum values

### 3. Customer Analysis
- Analyzed customer distribution based on gender and age
- Identified top spending customers

### 4. Product Category Analysis
- Compared sales across different product categories
- Identified high-performing product segments

### 5. Time Series Analysis
- Analyzed monthly sales trends
- Observed sales fluctuations across different months

### 6. Correlation Analysis
- Created a correlation heatmap
- Identified relationships between numerical variables

---

# Visualizations

## Gender Distribution
![Gender Distribution](Charts/gender_distribution.png)

---

## Product Category Sales
![Category Sales](Charts/category_sales.png)

---

## Age Distribution
![Age Distribution](Charts/age_distribution.png)

---

## Monthly Sales Trend
![Monthly Sales](Charts/monthly_sales.png)

---

## Top Spending Customers
![Top Customers](Charts/top_customers.png)

---

## Correlation Heatmap
![Heatmap](Charts/heatmap.png)

---

## Key Insights

- Certain product categories generated higher overall sales revenue.
- Customer purchasing behavior varied across different age groups.
- Sales trends changed across different months, indicating seasonal patterns.
- A small number of customers contributed significantly to total revenue.
- Quantity purchased showed a strong relationship with total transaction amount.

---

## Recommendations

1. Focus marketing efforts on high-performing product categories.
2. Improve customer retention strategies for valuable customers.
3. Analyze seasonal sales patterns for better inventory planning.
4. Develop targeted promotional campaigns for major customer groups.

---

## Project Structure

```text
Project_1_EDA
│
├── Charts
│   ├── age_distribution.png
│   ├── category_sales.png
│   ├── gender_distribution.png
│   ├── heatmap.png
│   ├── monthly_sales.png
│   └── top_customers.png
│
├── Dataset
│
├── README.md
│
└── EDA_Retail_Sales.ipynb
```

---

## Conclusion

This project successfully applied exploratory data analysis techniques on retail sales data to understand customer behavior, product performance, and sales trends. The insights generated from this analysis can help businesses make informed strategic decisions.
