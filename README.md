Data Analytics Internship – Task 20 (Customer Order Count)

This repository contains my submission for Task 20 of the Data Analytics Internship.

Dataset - Online Retail Dataset

Objective - The objective was to count orders per customer, identify frequent buyers, and understand basic customer ordering behavior.

Tools Used
1. Microsoft Excel
2. Online Retail Dataset
3. GitHub

Customer Order Analysis
1. Used the Online Retail Dataset containing 541,909 records.
2. Kept the original dataset unchanged in the Raw Data sheet.
3. Created a PivotTable using CustomerID and InvoiceNo.
4. Used Distinct Count of InvoiceNo to avoid counting multiple product lines from the same order as separate orders.
5. Excluded blank CustomerID values from the customer-level analysis.
6. Sorted customers by Order Count to identify frequent buyers.
7. Recorded the top five customers based on their order counts.

Top Customers
1. Customer ID 14911 – 248 orders
2. Customer ID 12748 – 224 orders
3. Customer ID 17841 – 169 orders
4. Customer ID 14606 – 128 orders
5. Customer ID 15311 – 118 orders

Files
1. Task 20.xlsx - Excel workbook containing Raw Data, PivotTable, and Customer Order Count sheets
2. README.md - Summary of the customer order analysis

Conclusion - Customer order frequency was successfully analyzed using distinct InvoiceNo counts for each CustomerID. The analysis identified the top five frequent buyers while avoiding duplicate order-line counting.
