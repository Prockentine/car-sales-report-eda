# Car Sales Report Exploratory Data Analysis

## Project Overview
This project focuses on analyzing a Car Sales dataset from Kaggle. The goal is to gain insights from the data by performing data gathering, exploration, manipulation, and creating visualizations. The main tools used for this project include pandas in Jupyter Notebook for data manipulation and Tableau for creating interactive and insightful visualizations.

## Tools & Technologies
  - **Kaggle** for the data set
  - **Pandas** for data manipulation and exploration
  - **Jupyter Notebook** for analysis and documentation
  - **Tableau** for interactive data visualization

## Datasource
The dataset used in this project was sourced from Kaggle's [Car Sales Report](https://www.kaggle.com/datasets/missionjee/car-sales-report), which contains details about car sales transactions, including:

Date of sale
Sales price
Customer demographic data
Dealership name and region
Car make, model, and body type

##Project Workflow
### 1. Data Gathering
  - The data was downloaded using the Kaggle API and loaded into a pandas DataFrame.
  - Data was imported and read into the Jupyter notebook for initial exploration using `pd.read_csv()`.

### 2. Data Exploration & Cleaning
  - Initial exploration was conducted to understand the structure of the dataset.
  - Key steps included:
      - Handling missing values: Identified and dealt with any missing or invalid data.
      - Data type conversion: Converted columns with inappropriate data types (e.g., converting dates to datetime).
      - Outlier detection: Analyzed price and quantity columns to detect and address outliers.
   
### 3. Data Manipulation
  - Filtered the data based on sales regions, car make, and sales dates to focus on specific insights.
  - Used aggregation functions (e.g., `groupby()`, `sum()`, `mean()`) to calculate total sales by region, car make, and other categories.
  - Created new columns, including calculating sales growth and percentage changes.

### 4. Data Visualization
  - Visualized the cleaned and aggregated data using Tableau for interactive insights:

## Results & Insights
  - **Sales Trends:** The analysis revealed key trends in car sales over time, with certain months showing spikes in sales.
  - **Regional Insights:** Sales were concentrated in specific regions, with higher sales numbers in urban areas.
  - **Top-Selling Cars:** Specific makes and models stood out as the most popular choices among customers.

## Conclusion
This project demonstrates the full data analysis workflow, from data gathering and manipulation using pandas to creating impactful visualizations with Tableau. It provides valuable insights into car sales trends, regional performance, and customer demographics.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

##Appendix

### Tableau Requirements
### Dashboard Purpose
The purpose of this dashboard is to present and overview of the sales data in order to analyze year-over-year sales performance to identify trends.
### Key Requirements
**KPI Overview**
  - Display a summary of total sales and quantity for the current year and previous year.
    
**Sales Trends**
  - Present the data for each KPI on a monthly basis for both the current year and the previous year.
  - Identify months with highest and lowest sales and make them easy to recognize.
    
**Dealership Comparison**
  - Compare sales performance by different dealers and regions for the current year and the previous year.
  - Include a comparison of sales by dealership region.
    
**Weekly Trends for Sales**
  - Present weekly sales data for the current year.
  - Display the average weekly values.
  - Highlight weeks that are above and below the average to draw attentio to sales and profit performance.
### Design & Interactivity Requirements
**Dashboard**
  - The dashboard should allow users to check historical data by offering them the flexibility to select any desired day/month/year.
  - Provide users with the ability to navigate between dashboards easily.
  - Make the chats and graphs interactive, enabling users to filter data using the charts.

**Data Filters**
  - Allow users to filter data by customer data like gender and annual income.
