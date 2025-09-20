# Amazon Sales Data Analysis

This project provides an end-to-end exploratory and analytical workflow on simulated Amazon sales data, combining Python-based data analysis with interactive dashboards and comprehensive reports.

## Contents

- **Analyzing_Amazon_Sales_data.ipynb**: Main Jupyter Notebook containing code for data loading, cleaning, analysis, and visualization.
- **Analyzing_Amazon_Sales_data.html**/**Analyzing_Amazon_Sales_data.pdf**: Rendered and exportable versions of the notebook for easy sharing or offline viewing.
- **Amazon Sales data.csv**: The core dataset (100 rows × 14 columns) containing sales records, regional sales, item categories, channels, pricing, revenues, costs, profits, and order dates.
- **Amazon Sales dashboard.pbix**: Power BI report offering an interactive sales dashboard based on the CSV data.
- **Amazon Sales dashboard pdf.pdf**: Exported PDF of the Power BI dashboard summarizing sales KPIs.

## Workflow & Analysis Steps

1. **Data Import & Cleaning**
   - Loads the sales CSV.
   - Converts columns (dates, numerics) to appropriate types.
   - Detects and fills missing values in `Total Cost`.
   - Ensures dataset integrity for analysis.

2. **Exploratory Data Analysis (EDA)**
   - Inspects data head, types, and summary statistics.
   - Generates heatmaps to verify data completeness.
   - Describes distribution of regions, channels, item types, and priorities.

3. **Business Analytics & Insights**
   - Highest/lowest revenue, profit, and units sold by region, country, and item type.
   - Detects top/bottom-performing categories and geographies.
   - Analyzes impact of sales channels on order priorities.
   - Measures order processing times and their variation by channel/country.
   - Calculates monthly trends and seasonality in revenue.

4. **Advanced Analysis**
   - Correlation between unit price and total profit.
   - Outlier detection in cost using boxplots and IQR.
   - Relationship exploration between units sold and profit.

5. **Visualization**
   - Multiple chart types: line plots, bar plots, pie charts, heatmaps, boxplots, scatter plots.
   - Power BI dashboard for interactive exploration and executive reporting.

## Getting Started

- Open the Jupyter notebook to reproduce and modify the Python analysis.
- Launch the PBIX file in Power BI Desktop for advanced dashboarding.
- Use the PDF/HTML summary files for sharing insights.

## Key Technologies

- **Python:** pandas, matplotlib, seaborn (for EDA & visualization)
- **Power BI:** Interactive dashboards & PDF exports
- **Jupyter Notebook:** Analysis scripting & documentation

## Example Insights

- **Top Region by Revenue:** Sub-Saharan Africa
- **Top Country by Profit:** Djibouti
- **Highest Selling Item Type:** Cosmetics
- **Fastest Order Processing (Channel):** Offline vs Online comparison
- **Order Priority Patterns:** Distribution across regions and channels

***

**Note:** This project is for educational and analytical demonstration, utilizing a simulated dataset.

***
