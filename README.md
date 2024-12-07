# MaxMin Manufacturing Power BI Report
This repository contains the Power BI report developed for MaxMinManufacturing. The report provides actionable insights into rejected products across their plants, machines, and time periods from 2013 to 2015. It is designed to support operational efficiency, the dashboard is interactive and allows stakeholders to drill down into specific areas of interest.<br><br>


**Table of Contents**
1. Project Objective

2. Tools and Techniques

3. Dataset Overview

4. Approach and Workflow

5. Key Insights
   
6. Future Enhancements.<br><br>


# Project Objective
The goal of this project was to create an interactive Power BI dashboard for MaxMin Manufacturing’s shift managers to analyze metrics related to rejected products, such as:

1. Total rejected products by plant and their respective countries.
   
2. Monthly trends in rejected products from 2013 to 2015.
   
3. Proportions of rejected products by machine type.<br><br>

# Tools and Techniques
-  SQL Server Management Studio (SSMS): To query and prepare raw manufacturing data.

-  Power BI: For building the dashboard and creating interactive visualizations.

-  Power Query: Used for cleaning, transforming, and shaping the data.

-  Data Modeling: Built relationships between datasets using snowflake schema principles for optimized reporting.<br><br>


# Dataset Overview #
The dataset includes information from MaxMin Manufacturing plants covering the period 2013 to 2015. Key data attributes include;

- Plant Information: Plant names, countries, and rejection statistics.

- Machine Data: Types of machines and their contribution to rejected products.

- Time Period: Monthly and yearly data for trend analysis.<br><br>


# Approach and Workflow
1.  **Data Extraction**
- Connected Power BI directly to SQL Server to query and retrieve only the necessary tables.
  
- Used SQL scripts to aggregate and pre-clean data before importing into Power BI.<br><br>

2. **Data Preparation**
- Applied Power Query to clean the data, remove redundancies, and handle missing values.
  
- Filtered data for the years 2013–2015 to maintain a focused analysis.<br><br>

  
3. **Data Modeling**
- Established relationships between tables using snowflake schema for efficient reporting.
  
- Created calculated columns and measures in DAX to derive insights such as total rejected products, proportions by machine type, and monthly trends.<br><br>
  
4. **Dashboard Development**
   
- Bar Charts: Visualized total rejected products by plant and grouped them by country.

- Line Chart: Displayed monthly trends for rejected products.

- Pie Chart: Illustrated the proportions of rejected products by machine type.<br><br>


5. **Interactivity Features**
- Incorporated drill-down/drill-up functionality to allow stakeholders to view detailed insights by plant, machine type, and specific months.
  
- Enabled hover-over tooltips with additional metrics for context.<br><br>


![Dashboard Screenshot](https://drive.google.com/uc?export=view&id=1XY_PzBuNwXHUg7rd0DR6xq-BN-ZcIrRp).<br><br>


# Key Insights

- **Plant Performance:** Fridley Plant in the USA had the highest rejected products with 64,195 over three years. Kawaguchi Plant in Japan had the lowest rejected products with 21,561, indicating variability in rejection rates across plant.<br><br>

- **Monthly Trends:** Peaks were observed in August and September, with approximately 9,600 rejected products each month across the 3 year period, highlighting potential seasonal production challenges.<br><br>

- **Machine Performance:** The Clay Molder machine was the top machine type for rejected products, contributing 40.28%, pointing to the need for preventive maintenance or process improvements.<br><br>
![Dashboard Screenshot](https://drive.google.com/uc?id=1V2s1CZB4fDa3w_J3HIsvrr4Ul2bc9ECZ)
![Dashboard Screenshot](https://drive.google.com/uc?id=1HptIYk5LneXF_G8c805JJR_eqhsGC13u).<br><br>
# Future Enhancements
The current dashboard meets MaxMinManufacturing's key requirements, but there are several opportunities to enhance its functionality:

- **Predictive Analytics:** Adding forecasting capabilities to help anticipate trends in rejected products and support proactive decision-making.<br><br>

- **Real-Time Integration:** Connecting the dashboard to live data sources for real-time reporting and actionable insights.<br><br>

- **Broader Metrics:** Expanding the analysis to include additional KPIs, such as production volumes, downtime, and defect rates, for a more comprehensive view of operations.<br><br>

# Link to Dashboard
[Explore the Dashboard](https://tinyurl.com/56yrpczw)
