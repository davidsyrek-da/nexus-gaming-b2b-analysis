# nexus-gaming-b2b-analysis
Advanced B2B Supply Chain &amp; Retailer Performance Analysis for Nexus Gaming. Built with Excel (Power Query &amp; Data Modelling) and Power BI.

Nexus Gaming B2B: Supply Chain & Retailer Performance Analysis

1. Project Overview
Nexus Gaming is a UK-based B2B wholesaler specialising in gaming hardware, software, and merchandise. This project demonstrates a complete data analysis lifecycle—from raw data ingestion to professional business intelligence reporting.

The goal is to provide the management team with insights into distribution efficiency, client profitability, and product performance across 10 key retail partners in the UK.

2. Business Objectives (KPIs)
The analysis focuses on answering the following strategic questions:

- Financial Health: What is the Total Revenue vs. Gross Profit across all categories?
- Distribution Reach: Which UK regions (Portsmouth, London, Manchester, etc.) are driving the highest order volumes?
- Client Segmentation: Who are our top-performing retail partners based on Average Order Value (AOV)?
- Operational Quality: How does the "Return Rate" impact our bottom line, and is there a correlation with "Customer Satisfaction" (Feedback Ratings)?

3. Technical Stack
This project is divided into two distinct phases to show a progression of analytical skills:

Phase 1: Microsoft Excel (Current Phase)
- Data Sourcing: Connecting to 4 separate raw data files (Dimensions & Facts).
- Power Query: Cleaning "dirty" data (inconsistent casing, date formats, and trailing spaces).
- Data Modelling: Establishing relationships between tables to create a "Star Schema" in Excel.
- Advanced Analytics: Using Power Pivot and complex formulas (IFS, XLOOKUP, measures) for financial logic.
- Interactive Dashboard: A dynamic visual interface with Slicers and Timelines.

Phase 2: Power BI (Upcoming)
- Migration of the Excel Data Model to Power BI Desktop.
- Advanced DAX (Data Analysis Expressions) for time-intelligence reporting.
- High-level interactive visualisations and automated reporting.

4. Data Architecture
The project utilizes a Relational Data Model consisting of:

- Dim_Products: Master list of 10+ products, categories, and costs.
- Dim_Clients: Details of 10 UK retail partners.
- Fact_Sales: 200+ transaction records from the 2025 fiscal year.
- Fact_Feedback: Customer satisfaction data linked to sales transactions.
