# 💳 Personal_Transaction_Insights_Dashboard

This project is an interactive Power BI dashboard that analyzes personal transaction history to generate actionable financial insights. It showcases data cleaning, transformation, and DAX-based metrics like Total Income, Total Expense, Net Balance, and Average Transaction Amount, alongside interactive visualizations for trends, top payees, and category-wise spending. Designed with a business-focused perspective, it demonstrates the ability to convert raw financial data into strategic insights.

## **Dataset & Preparation**
The dataset used in this project is **anonymized and synthetic** to ensure privacy. It originally contained the following columns:  

| Column Name          | Description |
|----------------------|-------------|
| **Date**             | Transaction date in `DD-MM-YYYY` format |
| **Transaction Details** | Description of the transaction (e.g., “Paid to EKART”) |
| **Type**             | Transaction type (`Credit` or `Debit`) |
| **Amount**           | Transaction amount in INR |
| **Transaction ID**   | Unique identifier for each transaction (hidden in dashboard for privacy) |
| **UTR No**           | Unique Transaction Reference number (hidden in dashboard for privacy) |
| **Account**          | Account number (removed due to high missing values and privacy) |

Sensitive columns (`Transaction ID`, `UTR No`, and `Account`) were **removed or hidden** in the dashboard.  

**Data Preparation Workflow:**  
1. Exported personal transaction data (PDF statements from banking apps).  
2. Converted PDF data to CSV using Python in Google Colab.  
3. Cleaned and transformed the data for Power BI, including:  
   - Standardizing date formats  
   - Categorizing transactions (Food, Shopping, Utilities)  
   - Creating calculated fields such as Month-Year for trend analysis  

## 📊 Key Features & Insights

- **Cash Flow Analysis** – Track income vs. expenses over time and calculate net balance.  
- **Spending Patterns** – Categorize transactions (Food, Shopping, Utilities) to identify top spending areas.  
- **Monthly Trends** – Visualize monthly income and expense trends to detect high-spending periods.  
- **Top Recipients & Payers** – Identify entities with the highest transactions.  
- **Average & Extreme Transactions** – Highlight typical transaction amounts and outliers.  
- **Interactive Dashboard** – Use slicers for Month, Category, and Transaction Type to explore insights dynamically.

  ##  Advanced Analytical Insights ✅
- Recurring vs one-time transactions to identify subscriptions  
- Forecasted monthly spending per category  
- Cash flow health indicators (net balance trends, savings %)  
- Spending heatmap by weekday and category  
- Top recipients/payees segmented by transaction category  
  
## 🖼️ Dashboard Layout
1. **Top KPIs Section:**  
   - Total Income 💵  
   - Total Expense 💸  
   - Net Balance 📊  
   - Average Expense 📌  
2. **Trends Section:**  
   - Line chart: Monthly Income vs Expenses 📈  
3. **Category Analysis Section:**  
   - Pie chart: Expense % by category 🥧  
   - Bar chart: Top recipients/payees 📊  
4. **Filters / Slicers:** Month-Year, Category, Transaction Type
   
## 🎯 Learning Outcomes / Skills Demonstrated
- Advanced **data cleaning and transformation** using Power Query  
- Creating dynamic and **advanced DAX measures**  
- Designing an **interactive and user-friendly Power BI dashboard**   
- Generating **actionable business insights** from financial data  
- Implementing **privacy-conscious data handling** 
- Storytelling with data: converting transaction patterns into **decision-ready insights**

    

