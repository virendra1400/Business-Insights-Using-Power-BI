# **Project Overview**

AtliQ Hardware is rapidly expanding its operations, and to gain a competitive edge in the market and make data-driven decisions, the company has undertaken the implementation of data analytics using PowerBi for the first time. This project aims to provide comprehensive insights for stakeholders across various domains, including finance, sales, marketing, and supply chain management.

## **Project Details**

I worked on this project following the Codebasics PowerBi Course, which provided valuable insights and guidance. The link to the course can be found here.

### **Live Report Link**

[Add Live Report Link here]

**Tech Stacks**

-SQL
-PowerBi Desktop
-Excel
-DAX language
-DAX studio (for optimizing the report)
-Project charter file

**PowerBI Techniques Learned**

-Critical pre-project questions
-Creating calculated columns
-Creating measures using DAX language
-Data modeling
-Using Bookmarks for visual switching
-Page navigation with buttons
-Utilizing the divide function to prevent zero division errors
-Creating date tables using M language
-Dynamic titles based on applied filters
-Implementing KPI indicators
-Conditional formatting for visuals using icons or background color
-Data validation techniques
-PowerBi services and report publishing
-Setting up a personal gateway for data auto-refresh
-PowerBi App creation
-Collaboration, workspace, and access permissions in PowerBi services
-And more 😅

**Business Related Terms**

Gaining familiarity with terms including but not limited to:

-Gross price
-Pre-invoice deductions
-Post-Invoice deductions
-Net Invoice sale
-Gross Margin
-Net sales
-Net profit
-COGC - cost of goods sold
-YTD - Year to Date
-YTG - Year to Go
-Direct
-Retailer
-Distributors
-Consumer

**Dataset Understanding**

Before delving into the analysis, a comprehensive understanding of the available dataset was crucial. The dataset comprises:
Dimension Table

    gdb041:
        dim_customer: 27 distinct markets, 75 customers, 2 types of platforms, 3 channels.
        dim_market: 27 distinct markets, 7 sub-zones, 4 regions.
        dim_product: Divisions, categories, and product variants.
        fact_forecast_monthly: Table for forecasting customer needs.
        fact_sales_monthly: Table containing sold quantities.
    gdb056:
        freight_cost: Details of travel costs per market.
        gross_price: Details of gross prices with product code.
        manufacturing_cost: Details of manufacturing costs with product code and year.
        Pre_invoice_dedutions: Details of pre-invoice deductions with customer and year.
        Post_invoice_deductions: Details of post-invoice deductions and related information.
