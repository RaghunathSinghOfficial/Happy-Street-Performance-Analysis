# Happy-Street-Performance-Analysis
# Elevate Labs Data Analyst Internship - Task 3: Happy Street Performance Analysis

## Project Overview

This repository contains the deliverables for **Task 3: Sales Dashboard** of the Elevate Labs Data Analyst Internship. The project focuses on providing data-driven insights into the 2023 performance of **Happy Street**, an innovative social entrepreneurship platform that empowers street food vendors through space management, customer support, and a "Buy Now, Pay Later" (BNPL) revenue model.

While the repository name specifies "Sales Dashboard," the project encompasses a broader analysis of Happy Street's core financial and customer acquisition performance, including revenue, expenses, customer acquisition cost (CAC), lifetime value (LTV), and profitability (burn rate).

The primary objective was to develop a comprehensive analytics framework, culminating in an interactive Power BI dashboard, to monitor key financial and customer acquisition metrics for 2023.

## Problem Statement

Happy Street, like many early-stage startups, needed a clear and concise way to track its operational efficiency, customer value, and overall financial health. The project addresses the need for:
- Monitoring monthly revenue and expenses.
- Tracking new customer acquisition (entrepreneurs).
- Analyzing key unit economics: Customer Acquisition Cost (CAC) and Lifetime Value (LTV).
- Assessing the LTV:CAC Ratio as a critical indicator of business viability.
- Understanding the overall profitability/burn rate.

## Key Performance Indicators (KPIs) Visualized

The interactive Power BI dashboard provides immediate insights into the following core KPIs for 2023:
- **Total Revenue**
- **New Entrepreneurs Acquired**
- **Average Customer Acquisition Cost (CAC)**
- **Average Lifetime Value (LTV)**
- **LTV:CAC Ratio**
- **Net Profit / (Loss)** (derived from Total Burn Rate)

## Tools and Technologies Used

- **Microsoft Excel:** Used for data organization and served as the primary data source for the simulated dataset.
- **Power Query (ETL):** Utilized for data ingestion, cleaning, transformation, and ensuring data quality across various sheets (`Customer Data`, `Monthly Financials`, `KPI Summary`).
- **Power BI Desktop:** Employed for advanced data modeling, creating calculated measures (DAX), and designing interactive and insightful dashboards.

## Project Structure and Deliverables

The repository contains the following key components:

1.  **`Happy_Street_Data_2023_Complete.xlsx`**:
    * The processed Excel dataset used for analysis. This file contains three sheets: `Customer Data`, `Monthly Financials`, and `KPI Summary`.
2.  **`Happy Street 2023 Performance Analysis Power BI Dashboard.pbix`**:
    * The Power BI Desktop file containing the complete data model, DAX measures, and the interactive dashboard. Users can open this file with Power BI Desktop to explore the dashboard.
3.  **`Happy Street 2023 Performance Analysis & Dashboard Report.pdf`**:
    * A concise 1-2 page PDF report summarizing the project's introduction, abstract, tools used, steps involved, and conclusions.

## Dashboard Highlights

The interactive Power BI dashboard allows users to:
- **Monitor overall performance** through prominent KPI cards.
- **Track monthly trends** for revenue, expenses, new customer acquisition, CAC, and LTV.
- **Filter data dynamically** by Date, City, and Customer Segment.
- **Analyze customer churn status**, a critical factor for business sustainability.

## Steps Involved in Building the Project

1.  **Data Generation & Preparation:**
    * Simulated a comprehensive dataset reflecting Happy Street's customer and financial operations for 2023.
    * Performed data cleaning and transformation in Power Query, ensuring correct data types and structure for analysis.
2.  **Data Modeling & DAX Measures:**
    * Imported data into Power BI Desktop.
    * Created essential DAX measures (`Total Monthly Expenses`, `Avg CAC (Monthly)`, `Avg LTV (Monthly)`, `Avg LTV:CAC Ratio (Monthly)`) for accurate calculations.
    * Applied consistent currency formatting across all relevant financial metrics.
3.  **Dashboard Design & Visualization:**
    * Designed an intuitive dashboard layout with a clear header, prominent KPI cards, trend charts, and interactive slicers.
    * Utilized various Power BI visuals (Card, Line Chart, Column Chart, Donut Chart, Slicer) to effectively communicate insights.
4.  **Interactivity and Finalization:**
    * Configured visual interactions to enable dynamic filtering and exploration.
    * Ensured consistent formatting and clear titles for all visuals.
    * Prepared a concise 1-2 page PDF report detailing the project.

## How to View the Dashboard

1.  **Download Power BI Desktop:** If you don't have it, download and install Power BI Desktop from Microsoft's official website.
2.  **Open the .pbix file:** Navigate and open `Happy Street 2023 Performance Analysis Power BI Dashboard.pbix` with Power BI Desktop.

---
