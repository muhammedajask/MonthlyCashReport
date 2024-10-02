# Monthly Cash Report for My Hotel

## Overview
Every month, our front office executive spends nearly an hour manually searching for collection amounts, sorting through various transaction types, and compiling a report for management. This tedious process not only consumes valuable time but also increases the chances of errors. 

To address this issue, I have taken several steps to create a monthly cash report for September 2024 that focuses on cash card and UPI transactions. By streamlining this process, we can significantly reduce the time required to generate the report.

### Steps Taken:
1. **Data Download**: Downloaded the transaction dataset named **CashierSep24** from the workplace system, which includes various types of transactions for September 2024.
2. **Data Conversion**: Converted the downloaded dataset into CSV format for easier manipulation and analysis.
3. **Data Cleaning and Transformation**: Loaded the CSV file into Excel Power Query for data cleaning and transformation, including removing unnecessary columns and ensuring data integrity.
4. **Column Quality Check and Filtering**: Analyzed column quality, formatted data types correctly, and filtered out null values while retaining only relevant payment modes (cash card and UPI).
5. **Grouping Data**: Utilized the "Group By" feature to aggregate data by date and payment mode, creating a new column called **Total Amount**.
6. **Pivoting Data**: Employed the "Pivot Column" feature to restructure the dataset, categorizing payment modes into separate columns without repeating dates.
7. **Loading into Excel and Final Formatting**: Loaded the transformed dataset into an Excel worksheet, created a table with total rows, added headings with the company name, and applied formatting to enhance visual appeal.

## Purpose
The purpose of this report is to provide management with a detailed overview of monthly transactions, specifically highlighting cash card and UPI collections. By optimizing this process, we aim to:
- **Reduce Manual Effort**: Eliminate the need for extensive manual searching and calculations.
- **Enhance Accuracy**: Minimize human error by relying on systematic data processing.
- **Improve Reporting Speed**: Enable quick access to financial insights, allowing for timely decision-making.

## Steps Taken

### Step 1: Data Download
- **Dataset Acquisition**: Downloaded the transaction dataset named **CashierSep24** from the workplace system. This dataset includes various types of transactions for September 2024, such as:
  - Cash Card Transactions
  - UPI Transactions
  - Online Transfers
  - TDS (Tax Deducted at Source)
  - TCS (Tax Collected at Source)
  - Other Transaction Types

### Step 2: Data Conversion
- **File Format Change**: Converted the downloaded dataset into CSV format to facilitate easier manipulation and analysis.

### Step 3: Data Cleaning and Transformation
- **Loading into Excel Power Query**: Imported the CSV file into Excel Power Query for data cleaning and transformation.
- **Data Cleaning Process**:
  - **Column Removal**: Removed all unnecessary columns from the dataset, retaining only the following relevant fields:
    - **Date**: The date of each transaction.
    - **Payment Mode**: The method used for payment (e.g., cash card, UPI).
    - **Payment Amount**: The amount associated with each transaction.
  - **Format Correction**: Ensured that all dates were in a consistent format and that payment amounts were correctly represented.
  - **Duplicate Removal**: Identified and eliminated any duplicate entries to ensure data integrity.

### Step 4: Column Quality Check and Filtering
- **Quality Assessment**: Analyzed the quality of each column to identify any issues such as missing values or incorrect formats.
- **Data Type Formatting**: Formatted columns into proper data types:
  - Ensured that the **Date** column was formatted as a date type.
  - Set the **Payment Mode** column as a text type.
  - Converted the **Payment Amount** column to a numeric type for accurate calculations.
- **Filtering Data**:
  - Filtered out rows with null values in the **Date** column to ensure all entries have valid dates.
  - Filtered the **Payment Mode** column to retain only transactions related to cash card and UPI.

### Step 5: Grouping Data
- **Grouping by Date and Payment Mode**:
  - Utilized the "Group By" feature in Power Query to aggregate data.
  - Grouped the dataset by both **Date** and **Payment Mode**, creating a new column called **Total Amount**.
  - This new column sums up all payment amounts for each payment mode on a particular date, allowing for clear visibility into total transactions.

### Step 6: Pivoting Data
- **Pivot Columns**: Employed the "Pivot Column" feature in Power Query to restructure the dataset.
  - This transformation categorized payment modes into separate columns while maintaining unique dates without repetition.
  - Each payment mode now has its own column, displaying total amounts corresponding to each date, facilitating easier comparison and analysis.

### Step 7: Loading into Excel and Final Formatting
- **Loading Data into Excel**: Loaded the transformed dataset into an Excel worksheet for final adjustments.
- **Table Creation**:
  - Converted the data range into an Excel table for better organization and readability.
  - Added total rows in the table to summarize overall cash card and UPI collections.
- **Report Formatting**:
  - Added a heading that includes the company name and report title for clarity.
  - Applied formatting styles (such as font size, colors, and borders) to enhance visual appeal and make the report attractive and easy to read.

## Final Output Report
The final output report is named **CashierReportSep24**, which provides a clear overview of cash card and UPI transactions according to their respective dates.

## Conclusion
The initial steps of downloading, converting, cleaning, checking column quality, filtering, grouping, pivoting, loading into Excel, and formatting have been successfully completed. The final report provides a clear overview of cash card and UPI transactions according to their respective dates.
