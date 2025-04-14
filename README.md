# Unified-Loan-Intelligence-Dashboard-Suite-Power-BI
Designed a comprehensive dashboard suite for a lending organization to monitor KPIs, understand borrower behavior, and analyze granular loan data.


1. 🔍 Overall Problem Statement: Unified Loan Insights Platform

The lending organization currently lacks a centralized analytics solution that brings together high-level performance tracking, borrower behavior insights, and granular loan-level data. Data is siloed across multiple tools and reports, leading to delayed decisions, inefficient analysis, and missed strategic opportunities.

To address these issues, a three-tiered dashboard ecosystem is being proposed:

Dashboard 1 focuses on high-level KPIs (Loan Applications, Funded Amount, Repayments, etc.) with Month-to-Date (MTD) and Month-over-Month (MoM) trend tracking.

Dashboard 2 explores borrower demographics, regional variations, and behavioral segmentation through visualizations.

Dashboard 3 offers a detailed, grid-style interface with full loan and borrower data for case-level review.

Together, these dashboards aim to provide a 360-degree view of loan operations, enabling smarter decisions, faster actions, and deeper insights.

2. 📄 Technical Requirement Document

Project Name: Unified Loan Intelligence Dashboard SuiteStakeholders: Risk Team, Lending Operations, Strategy Team, Customer Support, ExecutivesTools Suggested: Power BI / Tableau / Looker / Google Data Studio

Data Sources:

Loan Applications Table

Funded Loans Table

Repayment Transactions Table

Borrower Profiles Table

Regional Metadata (e.g., state, city)

Dashboard 1 – KPI Trends Dashboard

KPIs: Total Loan Applications, Total Funded Amount, Total Amount Received, Avg. Interest Rate, Avg. DTI

Time Views: MTD values, MoM percentage changes

Visuals: KPI Tiles, Line Charts (Monthly Trends), Bar Charts (MoM Growth/Decline)

Filters: Time Period, Loan Status, State

Dashboard 2 – Demographic & Regional Dashboard

Charts:

Line Chart: Monthly Trends by Issue Date

Filled Map: Lending by State

Donut Chart: Loan Term Distribution

Bar Chart: Employment Length vs Loan Metrics

Bar Chart: Loan Purpose Breakdown

Tree Map: Home Ownership Analysis

Metrics Displayed: Total Applications, Total Funded, Total Received

Filters: State, Employment Length, Loan Term, Purpose, Home Ownership

Dashboard 3 – Details Dashboard (GRID)

Fields: Loan ID, Borrower Name, Application Date, Loan Amount, Funded Date, Interest Rate, DTI, Repayment Status, State, Purpose, Employment Length, Home Ownership

Features: Search bar, dynamic filters, export functionality

Actions: Drilldown to view borrower/loan profile, sorting, pagination

3. 📊 UI Wireframe (Text-Based Description)

Dashboard 1 – KPI Trends

Top Row: 5 KPI Cards (Applications, Funded, Received, Avg Interest Rate, Avg DTI)

Center: Line Chart showing Monthly Trends for Applications, Funding, and Received Amounts

Bottom: Bar Charts showing MoM Growth Comparison per KPI

Dashboard 2 – Demographics View

Left Panel: Filters (State, Purpose, Home Ownership, Employment Length)

Center Grid:

Top Left: Line Chart (Monthly Trends)

Top Right: Filled Map (State-wise Lending Heatmap)

Middle: Donut Chart (Loan Term)

Bottom Left: Bar Chart (Employment Length)

Bottom Right: Tree Map (Home Ownership)

Dashboard 3 – Details Dashboard (GRID)

Top: Search Bar and Filters (Loan ID, Borrower Name, Date Range, Status)

Center: Table/Grid View with sortable columns and pagination

Bottom: Export to Excel / Drilldown Button

4. 🌟 Portfolio Case Study Format

Title: Building a Unified Loan Analytics Suite for Smarter Lending Decisions

Overview:Designed a comprehensive dashboard suite for a lending organization to monitor KPIs, understand borrower behavior, and analyze granular loan data.

Business Challenge:The client lacked a unified system to track loan performance metrics, demographic trends, and borrower-level data, leading to inefficiencies and poor strategic visibility.

Solution:

Created 3 dashboards:

KPI Dashboard with MTD/MoM insights on Applications, Funding, Repayments, Interest Rates, and DTI

Demographic Dashboard visualizing trends by geography, purpose, employment, and ownership

Details Dashboard with complete loan-level data in a searchable, filterable table

Impact:

Reduced manual reporting time by 70%

Enabled real-time loan monitoring

Helped identify regional and demographic lending opportunities

Empowered data-driven decision-making across teams

Tools Used: Power BI, SQL, Excel, Data Studio

My Role: Led the design, wireframing, data integration, and end-to-end development of all dashboards while collaborating with cross-functional stakeholders.
