# Apple-Regional-Sales-Analysis
**Short Description / Purpose**  
Power BI project turning Apple’s 2023–2024 quarterly PDFs into clear insights. I converted Financial statements to Excel, cleaned and modeled the data, and built a dashboard with simple formulas to track the KPI.  

**Tech Stack**  
- Power BI Desktop — visuals and DAX measures  
- Power Query / PowerPivot — data cleaning and reshaping  
- Excel — PDF-to-Excel conversion and staging  
- DAX (Data Analysis Expressions) — KPIs and YoY logic  
- Data Modeling — Calendar dimension related to fact tables  
- File formats — README and PNG preview (PBIX optional and not included in repo)  

**Data Source**  
Apple Inc. Investor Relations: quarterly PDFs for FY2023 and FY2024 — Condensed Consolidated Statements of Operations (Unaudited). Data extracted Q1–Q4 for each fiscal year and structured for analysis.  

**Features / Highlights**  
An interactive Power BI dashboard focused on Apple’s regional and product-category sales for fiscal years 2023 and 2024, with YoY comparisons calculated as 2024 versus 2023.  
- KPI card for total sales  
- Sales trend by product  
- Net sales by product category  
- Regional sales distribution with a sortable table  
- Sales growth percent for 2024 by region  
- YoY percent table for regions comparing 2024 to 2023  
- Slicers for Year (2023, 2024) and Quarter (Q1–Q4)  

**Business problem**  
Apple operates across multiple regions and product categories, making it essential to understand where sales are growing or slowing and which categories are driving performance. Stakeholders need a clear, consolidated view that compares 2024 against 2023.

**Goal of the dashboard**  
- Deliver an interactive dashboard with executive-level readability.  
- Highlight regional performance and product-category contributions.  
- Provide clear YoY comparisons of 2024 versus 2023.  
- Enable seasonal analysis using Year and Quarter slicers.  
- Support decision-making through intuitive visuals and KPIs.   

**Walkthrough of Key Visuals**  
- Total sales KPI  
- Line chart showing sales trend by product  
- Bar chart of sum of sales by region  
- Table of region and sales totals  
- Bar chart of sales growth percent in 2024 by region  
- Table showing net sales YoY percent by region with a total line  
- Slicers for Year and Quarter to change the context for all visuals  

**Business impact & Insights**  
Enables rapid comparisons between 2024 and 2023, makes regional slowdowns or accelerations immediately visible, clarifies which product categories lead or lag, and supports planning conversations by exposing seasonal patterns via quarter-level slicing.  

**Screenshots / Demos**  
The dashboard screenshot illustrates the regional and product views with the Year and Quarter slicers applied.  

**Problem Statements**  
- What are total sales by region in 2023 and 2024, and how do they compare year over year?  
- Which product categories contribute most to sales, and how does that mix shift between 2023 and 2024?  
- Which regions show the strongest or weakest growth in 2024 versus 2023?  
- How do quarter selections affect regional and category performance within each year?  

**Approach - Project Planning & Aims Grid**  
1. Purpose  
Convert Apple’s reported data into a consistent, model-driven dashboard summarizing full-year sales for 2023 and 2024 and clearly surfacing 2024 versus 2023 changes, with quarter-level filtering for seasonality.  

2. Stakeholders  
Finance leadership, Regional managers, executive decision-makers,sales team and marketing teams who need fast and reliable insights from standardized visuals and measures.  

3. End Result  
An interactive dashboard with validated totals, regional and product-category breakdowns, and documented refresh steps that can be reused for subsequent fiscal years.  

4. Success Criteria  
Reconciliation to Apple’s published totals for 2023 and 2024, correct YoY percent for 2024 versus 2023, a repeatable pipeline from source to model, and simple navigation using Year and Quarter slicers.  

**Data Analysis – Approach**  
- Collect FY2023 and FY2024 source data from Apple Investor Relations and focus on regional and product-category sales  
- Stage in Excel and reshape with Power Query into tidy tables for regions, products, and dates  
- Build a calendar dimension with Year and Quarter and relate it to the sales fact tables  
- Create DAX measures for total sales, YoY percent, and growth by region and by product  
- Design visuals to show sales by region, product category, growth percent by region, and a YoY percent table, controlled by Year and Quarter slicers  
- Validate totals and YoY outputs against the staged tables and exclude 2022 from scope  

---

**Disclaimer**  
This project is created solely for educational and demonstration purposes. It is not affiliated with or endorsed by Apple Inc. The data used in this dashboard is sourced from Apple’s publicly available Investor Relations reports. No confidential or proprietary information is included. Users should not rely on this project for financial decision-making or investment advice.  
