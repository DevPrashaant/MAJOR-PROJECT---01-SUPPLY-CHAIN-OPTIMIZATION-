# Supply Chain Optimization Project

## Project Overview

This project focuses on analyzing and optimizing supply chain operations by using real-world-style data. The goal is to identify inefficiencies in production, shipping, and supplier performance, and provide actionable insights through interactive dashboards and data visualizations using Python and Tableau.

## Objective

To explore, clean, and analyze supply chain data and develop interactive visualizations that help stakeholders:

- Monitor supplier performance and lead times  
- Understand product flow and shipping delays  
- Analyze production volumes and defect rates  
- Track key metrics like cost, availability, and revenue

## Tech Stack

- Python (Pandas, NumPy, Matplotlib)
- Tableau (Interactive dashboards and visualizations)
- Excel (Initial data review and manual preprocessing)

## Dataset Description

The dataset includes the following key metrics:

- Product type, SKU, Price, Availability
- Number of products sold, Revenue generated
- Customer demographics, Stock levels
- Lead times, Order quantities, Shipping times
- Shipping carriers, Shipping costs
- Supplier name, Location
- Production volumes, Manufacturing lead time, Manufacturing costs
- Inspection results, Defect rates
- Transportation modes, Routes, Costs

A simulated Start Date field was generated for Gantt-style timeline visuals.

## Project Workflow

1. Data Collection
- Loaded the dataset into Python using pandas
- Reviewed structure, data types, and missing values

2. Data Cleaning & Transformation
- Handled missing values
- Standardized column formats
- Simulated Start Date using Python for time-based visuals
- Exported clean dataset to .csv for Tableau use

3. Exploratory Data Analysis (EDA)
- Analyzed key metrics like revenue, costs, shipping times, defect rates, and lead times
- Created summary tables and initial visual plots to find patterns

4. Visualization in Tableau

Created an interactive dashboard in Tableau with the following visuals:

| Visualization Type | Purpose |
|--------------------|---------|
| Bar Chart | Compare revenue by product type and supplier |
| Line Chart | Track production volume or lead time trends |
| Pie Chart | Show distribution of inspection results, shipping carriers, or product categories |
| Circle Plot | Compare defect rates vs stock levels |
| Text Cards (KPIs) | Display total revenue, average lead time, total defects, etc. |
| Gantt-Style Chart | Visualize production or shipping timelines per product or supplier using Start Date + lead time |

Filters included: Product Type, Supplier, Location, Transportation Mode

5. Insights & Recommendations
- Identified suppliers with the longest lead times and highest defect rates
- Highlighted shipping carriers with the highest average costs
- Found product types contributing the most to revenue but suffering from delays
- Recommended supplier adjustments and cost-saving opportunities

## Sample Insights

- Supplier X had consistently higher lead times and higher defect rates.
- Transportation by air was fastest but had the highest costs.
- Product Type B contributed to 40% of revenue but suffered shipping delays in certain regions.

## How to Use This Project

1. Clone/download this repository  
2. Open supply_chain_data_with_dates.csv in Tableau  
3. Explore or modify the dashboard views based on your analysis goals

## Files Included

| File Name | Description |
|-----------|-------------|
| supply_chain_data_with_dates.csv | Cleaned dataset with simulated Start Date |
| README.md | Project overview and documentation |
| supply_chain_dashboard.twbx | Tableau workbook with dashboards |
| supply_chain_analysis.ipynb | Python notebook for cleaning and simulation |

## Role & Contribution

As the data analyst, I was responsible for:
- Data cleaning and preparation
- EDA and insights development
- Visualization and dashboard creation in Tableau
- Final recommendations based on findings


