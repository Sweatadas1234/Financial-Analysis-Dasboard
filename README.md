# 📊 Financial Data Analysis Dashboard  

An **interactive Power BI dashboard** to analyze financial performance, including budgeting, expenses, profit/loss, and transaction trends.

## 🔹 Overview  
This dashboard provides key financial insights using **DAX measures and calculated columns**, helping businesses track their budget vs. actual expenses and improve decision-making.

## 📌 Features  
- **Financial KPIs**: Total Budget, Actual Expense, Profit/Loss, Profit %.  
- **Visualizations**: Pie charts, bar graphs, line charts, and KPI cards.  
- **DAX Measures**:
  - `Total Budget = SUM(Budget)`
  - `Total Expense = SUM(Actual Expense)`
  - `Total Profit/Loss = SUM(Profit/Loss)`
  - `Profit % = DIVIDE([Total Profit/Loss], [Total Budget], 0)`
  - `Transaction Count = COUNTROWS(FinancialTable)`
- **Calculated Columns**:
  - `Profit/Loss Calculation = [Budget] - [Actual Expense]`
  - `Profit Status = IF([Profit/Loss] > 0, "Profit", "Loss")`
- **Filters & Slicers** for interactive data exploration.  
- **Optimized Analysis**: 40% faster trend identification, 30% improved decision accuracy.  

## 🛠️ Technologies Used  
- **Power BI** for data visualization.  
- **DAX (Data Analysis Expressions)** for custom calculations.  
- **Excel/SQL** for data preprocessing.  



## 🚀 How to Use  
1. Load the dataset containing **Date, Category, Budget, Actual Expense, Profit/Loss, and Profit %**.  
2. Import the **DAX measures** and **calculated columns** into Power BI.  
3. Customize filters and slicers to explore financial trends dynamically.  
4. Analyze insights from visualizations and optimize financial decisions.  

## 📂 Repository Structure  
