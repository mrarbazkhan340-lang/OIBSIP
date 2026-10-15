# Exploratory Data Analysis on Retail Sales Data

## Project Overview

This project explores retail transaction data using Python to understand sales trends, customer demographics, and product category performance.

The analysis uses data cleaning checks, descriptive statistics, and visualizations to identify patterns and develop actionable business recommendations.

## Objectives

- Inspect the dataset and check data quality.
- Analyze monthly and quarterly sales trends.
- Explore transactions by gender and customer age group.
- Compare revenue and quantity sold across product categories.
- Examine correlations between numerical variables.
- Develop business recommendations based on the findings.

## Dataset Information

- **Total records:** 1,000 transactions
- **Total columns:** 9
- **Time period:** January 2023 to January 2024
- **Product categories:** Electronics, Clothing, and Beauty

### Dataset Columns

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

The dataset contains transaction-level information. It does not include individual product names or profit margins.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preparation

The following checks and preparation steps were performed:

- Loaded the CSV file using Pandas.
- Inspected the dataset dimensions, columns, and data types.
- Checked for missing values and duplicate rows.
- Checked for duplicate transaction IDs.
- Converted the Date column to datetime format.
- Checked whether Total Amount equals Quantity multiplied by Price per Unit.
- Created age groups for demographic analysis.

No missing values or duplicate rows were reported in the initial checks. No transaction amount mismatches were found.

## Analysis and Visualizations

### 1. Monthly Sales Trend

Analyzed monthly sales to identify fluctuations and stronger or weaker sales periods.

### 2. Quarterly Sales Trend

Compared sales across quarters in 2023. Q4 recorded the highest full-quarter sales.

### 3. Gender Analysis

Compared transaction counts and revenue by gender.

### 4. Customer Age-Group Analysis

Grouped customers into five age ranges to examine the distribution of transactions.

### 5. Revenue by Product Category

Compared total revenue across Electronics, Clothing, and Beauty.

### 6. Quantity Sold by Product Category

Identified which product category recorded the highest sales volume.

### 7. Correlation Heatmap

Examined linear relationships between age, quantity, price per unit, and total amount.

### 8. Additional Analysis: Revenue by Gender

Compared total revenue and average transaction value across gender groups.

## Key Findings

- Electronics generated the highest category revenue of **156,905**.
- Clothing recorded the highest quantity sold, with **894 units**.
- Beauty recorded category revenue of **143,515** and quantity sold of **771 units**.
- May 2023 recorded the highest monthly sales at **53,150**.
- September 2023 recorded the lowest full-month sales at **23,620**.
- Q4 2023 recorded the highest quarterly sales at **126,190**.
- The 46–55 age group recorded the highest transaction count, with **229 transactions**.
- Female transactions generated **232,840** in revenue, compared with **223,160** for male transactions.
- Price per Unit and Total Amount showed a correlation of **0.85**.

## Business Recommendations

1. Investigate the sales decline in September and the stronger sales periods in May and Q4 to improve campaign planning.
2. Monitor Clothing inventory because it recorded the highest unit volume.
3. Review Beauty category performance before deciding whether targeted promotions or product assortment changes are needed.
4. Compare spending and category preferences across age groups to support customer segmentation.
5. Separate incomplete reporting periods from full months or quarters when comparing sales performance.

## Limitations

- The dataset does not contain individual product names, so the top 10 individual products cannot be identified.
- Profitability cannot be assessed because product costs and profit margins are unavailable.
- Correlation does not establish causation.
- January 2024 contains only a small amount of recorded sales and should be treated as a potentially incomplete reporting period.
- The observed sales patterns do not establish why sales increased or decreased.

## How to Run the Project

1. Clone or download the repository.
2. Install the required Python libraries.
3. Open the project notebook in Jupyter Notebook or VS Code.
4. Ensure the CSV file is located in the `data/` directory.
5. Run the notebook cells from top to bottom.

Install the required libraries with:

```bash
pip install pandas matplotlib seaborn jupyter
```

## Project Structure

```text
DataAnalytics-L1-EDARetailSales/
├── data/
│   └── retail_sales_dataset.csv
├── screenshots/
├── README.md
└── retail_sales_analysis.ipynb
```

## Conclusion

This project demonstrates how exploratory data analysis can help summarize retail sales performance, identify category-level patterns, and understand customer transaction distributions. The findings provide a starting point for further investigation and data-driven business decisions.

---

**Project Track:** Data Analytics
**Internship:** Oasis Infobyte
**Task:** Level 1 — Exploratory Data Analysis on Retail Sales Data