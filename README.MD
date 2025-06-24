# SAP ABAP Sales Order Summary Report (ALV)

This project contains an SAP ABAP ALV report (`ZSA_ALV_REPORT_PROJECT`) to display summarized sales order data.

 Features
- Displayed sales order headers and item details based on user input
- Displayed data using REUSE_ALV_GRID_DISPLAY with sorting, subtotals and auto column width
- Implemented error handling for no data and alv display issues

 Requirements
- SAP NetWeaver system
- Sales Order Table: `VBAK`, `VBAP`.
- Custom Selection Screen with Parameters

 How to Use
1. Create a program in `SE38`: `ZSA_ALV_REPORT_PROJECT`.
2. Paste the code from : `ZSA_ALV_REPORT_PROJECT.ABAP`.
3. Activate and execute.

1. ALV Output
![ALV Output](ALV_SALES_ORDER_SUMMARY_OUTPUT.PNG)

2. Filtered Sales Orders
![Filter on sales document](FILTER_ON_SALES_DOCUMENT.PNG)

Download the sample ALV Excel output:  
[ALV_GRID_PROJECT.xlsx](ALV_GRID_PROJECT.xlsx)


AUTHOR:
SANKIRTHANA VINDYALA
