# 📊 Sales & Revenue MIS Dashboard | Microsoft Excel

An interactive **Sales & Revenue Management Information System (MIS) Dashboard** built using Microsoft Excel to analyze business performance across regions, product categories, sub-categories, products, discount bands, shipping modes, and time periods.

This project demonstrates how Excel-based reporting and business analysis can help management monitor key performance indicators (KPIs), identify trends, evaluate profitability, and make data-driven business decisions.

---

## 📌 Project Overview

The Sales & Revenue MIS Dashboard is designed to provide a consolidated view of sales performance and profitability through interactive reports and visualizations.

The workbook uses a sales dataset containing **100,000 rows** and multiple business attributes, including sales, profit, quantity, discounts, products, customers, regions, and order and shipping dates.

The dashboard combines KPI cards, PivotTables, PivotCharts, interactive slicers, and management insights to make business performance easier to understand.

**Project type:** Sales MIS Reporting and Business Analysis  
**Tool:** Microsoft Excel  
**Dataset size:** 100,000 rows  
**Focus areas:** Sales performance, profitability, product analysis, regional analysis, discount analysis, and management reporting

### 📂 View the Excel Project

**[Open the Sales & Revenue MIS Dashboard on OneDrive](https://1drv.ms/x/c/b68e180ff513321e/IQANhiEuNfPPTaxSXgBvwSIyAWv3kiRI371g_iMWQ20dKtg?e=qFPJ7N)**

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Monitor overall sales, profit, profit margin, order volume, and quantity sold.
- Compare sales and profit performance across different regions.
- Analyze product categories, sub-categories, and individual products.
- Track monthly sales trends and year-over-year performance.
- Evaluate the relationship between discount levels and profitability.
- Compare performance across shipping modes.
- Create interactive reports that allow users to explore business performance.
- Prepare management insights and recommendations to support business decisions.

---

## 🧩 Business Problem

Businesses generate large volumes of sales transactions, making it difficult for management to understand overall performance by reviewing raw data alone.

Without consolidated reporting, managers may struggle to answer questions such as:

- How much revenue has the business generated?
- How much profit has been earned?
- Which regions contribute the most to sales and profit?
- Which product categories and products perform best?
- How do discounts relate to sales and profitability?
- How have sales changed over time?
- Which areas may require further investigation or improvement?

This project addresses these questions by organizing sales information into an interactive Excel MIS dashboard and supporting management reports.

---
## 📁 Dataset Overview

The project uses a sales dataset containing **100,000 rows and 27 columns**, covering customer information, sales transactions, product details, geographical dimensions, shipping information, and calculated business metrics.

### Complete Column List

1. Customer ID
2. Customer Name
3. Date of Birth
4. Sales
5. Year
6. Outlet Type
7. City Type
8. Category of Goods
9. Region
10. Country
11. Segment
12. Sales Date
13. Order ID
14. Order Date
15. Ship Date
16. Ship Mode
17. State
18. Postal Code
19. Product ID
20. Sub-Category
21. Product Name
22. Quantity
23. Discount
24. Profit
25. Discount Band
26. Shipping Days
27. Profit Margin

### Calculated Fields

**Discount Band:** Groups transactions into discount ranges to support discount-level sales and profitability analysis.

**Shipping Days:** Measures the number of days between the order date and ship date, supporting shipping-time analysis.

**Profit Margin:** Measures profit relative to sales, helping compare profitability across products and other business dimensions. The calculation should use the workbook's actual formula and percentage format.

These fields support analysis across sales, profitability, products, regions, discounts, and shipping performance.
## 🛠️ Tools and Technologies

### Microsoft Excel

Microsoft Excel is the primary tool used to build the MIS reporting solution.

**Excel features used:**

- **Excel Tables:** Organize the source data into a structured format.
- **Excel formulas:** Calculate KPIs, ratios, percentages, and supporting metrics.
- **PivotTables:** Summarize large datasets by region, category, product, month, year, and discount band.
- **PivotCharts:** Convert summarized results into visual reports.
- **Slicers:** Filter dashboard analysis by selected dimensions such as year, region, category, and shipping mode.
- **KPI cards:** Present key business metrics in a concise format.
- **Dashboard design:** Arrange metrics and charts into a management-friendly view.
- **MIS reporting:** Summarize performance, identify trends, and communicate business findings.

The project focuses on practical Excel reporting and analysis rather than programming-based automation.

---

## 🔄 Data Analysis and Reporting Process

The project follows a structured reporting workflow:

### 1. Source Data

Use the available sales dataset containing transaction-level information.

### 2. KPI Calculations

Calculate the main performance metrics, including total sales, total profit, profit margin, transaction quantity, order count, and average discount.

### 3. PivotTable Analysis

Summarize the data by different business dimensions, such as region, category, product, month, year, and discount band.

### 4. Visual Reporting

Create PivotCharts to communicate comparisons and trends clearly.

### 5. Interactive Dashboard

Bring the key performance indicators and charts together on a single dashboard with slicers for interactive filtering.

### 6. MIS Insights Report

Interpret the summarized results and prepare business observations and recommendations.

### 7. Management Decision Support

Use the reports to identify strong-performing areas and opportunities that deserve further investigation.

---

## 📈 Key Performance Indicators (KPIs)

The dashboard contains the following primary KPIs.

| KPI | Purpose |
|---|---|
| Total Sales | Measures the total sales value |
| Total Profit | Measures the total profit generated |
| Profit Margin | Shows profit as a percentage of sales |
| Total Orders | Displays the count of order records |
| Total Quantity | Measures the total units sold |
| Average Discount | Measures the average discount in the dataset |

### KPI Calculation Logic

**1. Total Sales**

Sum of the Sales field.

**2. Total Profit**

Sum of the Profit field.

**3. Profit Margin**

Profit margin measures the share of sales retained as profit.

Formula:

`Profit Margin = (Total Profit / Total Sales) × 100`

**4. Total Orders**

The workbook currently uses a count of Order ID records. This should be interpreted as a record count unless the analysis explicitly calculates distinct order IDs.

**5. Total Quantity**

Sum of the Quantity field.

**6. Average Discount**

Average of the Discount field, displayed as a percentage when the underlying values use percentage fractions.

These KPIs provide a high-level overview of business performance and support deeper analysis through the dashboard.

---

## 📊 PivotTable Analysis

PivotTables are used to summarize the transaction-level dataset and compare business performance across different dimensions.

### 1. Regional Sales and Profit Analysis

Compares sales and profit across regions.

**Business purpose:**
- Understand regional sales contribution.
- Compare profitability across markets.
- Identify regions that may need additional analysis.

### 2. Category Performance Analysis

Compares sales and profit across product categories.

**Business purpose:**
- Identify major contributors to revenue.
- Compare profitability between categories.
- Support category-level performance reviews.

### 3. Monthly and Yearly Trend Analysis

Summarizes sales and profit over time.

**Business purpose:**
- Monitor changes in sales performance.
- Identify growth or decline across periods.
- Support periodic reporting and planning.

### 4. Sub-Category Performance Analysis

Analyzes sales and profit at the product sub-category level.

**Business purpose:**
- Compare smaller product groups.
- Identify high-revenue or low-profitability areas.
- Support product portfolio reviews.

### 5. Product-Level Analysis

Compares individual products by sales and profitability.

**Business purpose:**
- Identify products contributing strongly to revenue.
- Compare product profit performance.
- Support product-level business reviews.

### 6. Discount Band Analysis

Groups transactions into discount ranges and compares their sales and profit performance.

**Business purpose:**
- Understand how performance varies across discount levels.
- Investigate whether higher discounts coincide with lower profitability.
- Support future discount-policy reviews.

### 7. Shipping Mode Analysis

Compares performance across shipping methods.

**Business purpose:**
- Review sales and profit across shipping modes.
- Identify differences in business performance.
- Support further investigation into shipping and service decisions.

---

## 🎛️ Interactive Dashboard

The **Sales & Revenue MIS Dashboard** combines the most important business metrics and charts into one reporting interface.

### Dashboard Components

#### KPI Cards
- Total Sales
- Total Profit
- Profit Margin
- Order Count
- Total Quantity
- Average Discount

#### Monthly Sales Trend
Displays sales performance over time to help identify trends and changes between periods.

#### Sales by Region
Compares sales contribution across geographical regions.

#### Sales vs. Profit by Category
Compares revenue and profitability across product categories.

#### Top 10 Products by Sales and Profit
Highlights selected top-performing products based on sales and profit measures.

#### Sales and Profit by Discount Band
Compares performance across discount ranges.

### Interactive Slicers

The dashboard includes slicers for:

- Year
- Region
- Category of Goods
- Ship Mode

Users can select one or more values to explore different segments of the business. Dashboard figures and connected PivotCharts update according to the selected filters, provided the relevant PivotTables and charts share the slicer connections.

### Why the Dashboard Matters

Instead of manually reviewing many rows of data, management can use the dashboard to:

- Monitor key performance metrics quickly.
- Compare different business segments.
- Investigate performance changes.
- Review sales and profitability patterns.
- Explore filtered views for reporting and decision support.

---

## 📝 MIS Reports

The workbook includes supporting analysis designed to turn summarized data into useful management information.

### 1. Sales Performance Report

Summarizes total sales and compares performance across regions, product categories, and time periods.

**Management use:** Monitor revenue performance and identify areas that warrant attention.

### 2. Profitability Report

Examines total profit and profit margin across selected business dimensions.

**Management use:** Understand where profits are generated and identify areas for deeper profitability analysis.

### 3. Regional Performance Report

Compares regional sales and profit contribution.

**Management use:** Review geographical performance and investigate differences between regions.

### 4. Product Performance Report

Evaluates sales and profit at category, sub-category, and product levels.

**Management use:** Support product portfolio reviews and identify products for further investigation.

### 5. Discount Analysis Report

Examines sales and profit across discount bands.

**Management use:** Investigate how discounting relates to profitability and support evidence-based discount decisions.

### 6. Time-Based Performance Report

Analyzes monthly and yearly sales and profit trends, including year-over-year growth.

**Management use:** Track changes over time and identify periods requiring further investigation.

### 7. Shipping Mode Performance Report

Compares results across shipping modes.

**Management use:** Review performance differences across shipping methods and investigate possible operational factors.

### 8. Management Insights and Recommendations Report

Summarizes key findings from the analysis and translates them into potential business actions.

**Management use:** Communicate important observations clearly and support business discussions.

---

## 💡 Business Insights and Recommendations

The workbook's analysis is intended to help identify patterns and areas for further investigation. Recommendations should be based on the actual values shown in the PivotTables and dashboard.

### Regional Performance
Compare regional sales and profit to identify high-contribution regions and areas that may need improvement.

**Potential recommendation:** Investigate the drivers of regional differences before changing sales targets, resource allocation, or regional strategy.

### Product Profitability
Compare product sales with product profit to distinguish high-revenue products from products that contribute strongly to profit.

**Potential recommendation:** Review product costs, pricing, and discounting before making product-level decisions.

### Discount Performance
Compare profit and sales across discount bands to understand whether higher discount levels are associated with different profitability outcomes.

**Potential recommendation:** Evaluate discount policies using both sales and profit rather than sales alone.

### Sales Trends
Review monthly and yearly performance to identify periods of growth or decline.

**Potential recommendation:** Investigate the causes of significant changes and use verified patterns to support future planning.

### Category and Sub-Category Performance
Compare revenue and profit across product groups.

**Potential recommendation:** Examine low-profitability categories to determine whether pricing, costs, product mix, or discounting may be contributing factors.

### Shipping Mode Performance
Compare sales and profit across shipping modes.

**Potential recommendation:** Investigate shipping cost, delivery time, and customer-service measures before changing shipping policies.

**Important:** These are decision-support recommendations, not claims that a particular business problem has already been proven by the dataset. Actual conclusions should be tied to the results in the workbook.

---

## 🧠 Excel Skills Demonstrated

This project demonstrates practical skills relevant to entry-level Data Analyst, MIS Executive, and MIS Analyst roles.

- Structuring and working with large datasets in Excel
- Writing formulas for business KPIs
- Calculating totals, averages, ratios, and percentages
- Building PivotTables for multidimensional analysis
- Creating PivotCharts for visual reporting
- Designing KPI cards
- Connecting slicers to interactive reports
- Analyzing sales and profit trends
- Comparing regional and product performance
- Performing discount and shipping-mode analysis
- Preparing management reports
- Communicating business findings through data visualization

---

## 🚀 How to Explore the Project

1. Open the [Excel workbook on OneDrive](https://1drv.ms/x/c/b68e180ff513321e/IQANhiEuNfPPTaxSXgBvwSIyAWv3kiRI371g_iMWQ20dKtg?e=qFPJ7N).
2. Review the Sales & Revenue MIS Dashboard.
3. Examine the KPI cards to understand the overall performance measures.
4. Use the slicers to filter results by year, region, category, and shipping mode.
5. Review the PivotTables to understand the underlying summaries.
6. Explore the charts to compare sales, profit, product performance, and discount bands.
7. Review the MIS Insights report for findings and recommendations.

For the best experience, open the workbook in Microsoft Excel if some interactive features do not behave the same way in the browser.

---

## ⚠️ Project Limitations

- The project focuses on analysis and reporting using the available dataset.
- Data cleaning was not a major component of this project.
- The analysis reflects the fields and information available in the dataset.
- A count of Order ID records may differ from the number of distinct orders.
- Relationships observed between discounts, sales, profit, and shipping modes do not automatically establish causation.
- The workbook is an Excel-based reporting solution; automated database connections, scheduled refreshes, and VBA automation are not claimed as part of this project.

---

## 🏁 Conclusion

The Sales & Revenue MIS Dashboard demonstrates how Microsoft Excel can be used to transform a large sales dataset into an interactive reporting solution.

By combining KPI calculations, PivotTables, PivotCharts, slicers, and management insights, the project provides a structured approach to monitoring sales performance, analyzing profitability, comparing business segments, and supporting data-driven decisions.

This project reflects practical Excel and business-analysis skills applicable to **Data Analyst, MIS Executive, and MIS Analyst** opportunities.

---

## 👤 Author

**Dileep Kumar Mallela**

Aspiring Data Analyst | MIS Analyst | MIS Executive

**Technical Skills:** Microsoft Excel, SQL, Power BI, Python, Pandas, NumPy, MySQL

**Project:** Sales & Revenue MIS Dashboard

**Workbook:** [View the project on OneDrive](https://1drv.ms/x/c/b68e180ff513321e/IQANhiEuNfPPTaxSXgBvwSIyAWv3kiRI371g_iMWQ20dKtg?e=qFPJ7N)

---

*This project was developed for practical learning and portfolio demonstration of Excel-based MIS reporting and business analysis.*
