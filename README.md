# Online-Retail-Sales-Dashboard-Power-BI
This Power BI dashboard provides a comprehensive analysis of an online retail dataset from an e-commerce store. The dashboard focuses on sales trends, customer behavior, and product performance across different countries and time periods.

Key Features
Dynamic filtering using slicers.
Excludes United Kingdom in selected visuals to highlight global performance.
Proper date hierarchy setup (Year → Month)

Clean DAX measures:
Total Revenue
Total Orders using DISTINCTCOUNT(InvoiceNo)
Products Sold using SUM(Quantity)
Average Unit Price

📁 Dataset
The dataset used is Online Retail.xlsx, which includes:
CustomerID, Country, InvoiceNo, InvoiceDate , Product Description, StockCode,  Quantity, UnitPrice

📎 Use Case
Ideal for e-commerce analysts, BI developers, and data enthusiasts looking to build or explore:
Sales dashboards
Country-wise performance
Time series trends

