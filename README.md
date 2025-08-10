# DA-capstone
Impact of Mobile Money on Financial Inclusion in Kenya: Data Analytics Capstone Project Proposal

***

## Project Title
Analyzing the Role of Mobile Money in Enhancing Financial Inclusion in Kenya

***

## Project Description
This capstone project investigates the impact of mobile money platforms, primarily M-Pesa, on financial inclusion in Kenya. By analyzing data from various sources, including Safaricom, the Kenya National Bureau of Statistics and the Central Bank of Kenya, the project aims to quantify the relationship between mobile money adoption and key financial inclusion metrics like bank account ownership and transaction frequency. 

***

## Problem Statement
Despite the widespread adoption of mobile money in Kenya, the relationship between its use and traditional financial inclusion metrics, such as bank account ownership and formal credit access, remains poorly understood. This project addresses the gap by examining how the adoption of M-Pesa impacts financial inclusion across different counties and demographic groups. It will identify specific regional and demographic disparities to inform targeted interventions that can help bridge the financial divide and promote equitable economic growth.

***

## Research Questions
1. How has the adoption of M-Pesa influenced bank account ownership rates across urban and rural Kenyan counties?
2. What are the disparities in M-Pesa transaction volumes between different regions and demographics in Kenya?
3. How do average transaction volumes vary by county, and what factors contribute to these variations?
4. What is the correlation between M-Pesa transaction frequency and key financial inclusion metrics, such as account ownership?
5. How have yearly transaction values for peer-to-peer (P2P) transfers evolved over time in Kenya?
6. What is the distribution of M-Pesa agents across Kenyan counties, and how does it relate to adoption rates?
7. How do M-Pesa adoption rates and financial inclusion metrics differ by demographic groups, such as rural women?
8. What trends are observed in monthly M-Pesa transaction volumes over time, and how do they impact financial inclusion?
9. Which Kenyan counties exhibit high M-Pesa usage but low overall financial inclusion, and why?
10. What is the spatial distribution of financial inclusion metrics, like percentage of population with mobile money accounts, across Kenyan counties?

***

## Target Audience
* **Policymakers:** To inform regulations and policies that promote financial inclusion.
* **Financial Institutions:** To develop new products and services that cater to mobile money users.
* **Economists & Researchers:** To provide a data-driven foundation for further socioeconomic studies on digital finance.
* **NGOs:** To guide targeted interventions and financial literacy programs for underserved populations.

***

## Planned Features
* **Data Collection & Cleaning:** Utilize Python to scrape data from safaricom, cbk and knbs, followed by cleaning and preprocessing using Pandas and NumPy.
* **Exploratory Data Analysis (EDA):** Analyze distributions, correlations and trends in mobile money usage and financial inclusion data.
* **Data Storage & Querying:** Set up MySQL to store and query the structured data.
* **Visualizations:** Use python to create a mix of static, interactive and geospatial visualizations to tell a comprehensive data story.
* **Tableau Dashboard:** Develop a dynamic dashboard with KPIs and filters to present key findings.
* **Insights & Recommendations:** Generate a report summarizing key findings and offering actionable recommendations based on the analysis.

***

## Technologies / Concepts
Tools and techniques used for data analysis, querying, and visualization:
* **Python:** The primary tool for data scraping, wrangling , and visualization.
* **SQL (MySQL):** For database management, data storage, and efficient querying of large datasets.
* **Tableau:** To create interactive dashboards and key performance indicator (KPI) visualizations.
* **Geopandas:** For geospatial analysis and creating choropleth maps of Kenya.

***

## Data Source
* **Primary Sources:**
    * Safaricom Annual Reports: Transaction volumes, number of registered M-Pesa users, and agent network data.
    * Kenya National Bureau of Statistics (KNBS): Financial inclusion surveys, county-level demographic data, and economic indicators.
    * Central Bank of Kenya (CBK): Data on mobile money penetration, value of transactions, and policy documents.
* **Data Collection Method:** Use BeautifulSoup, a python library to scrape data from websites and PDF documents.
* **Data Cleaning:** Use Pandas for initial data cleaning, including handling missing values, standardizing formats and removing outliers.

***

## Success Criteria
The project will be considered successful if it:
* Successfully collects, cleans, and integrates data from all specified sources.
* Produces a functional and insightful Tableau dashboard with interactive features.
* Answers all research questions with data-driven conclusions.
* Provides actionable recommendations for policymakers and financial institutions to enhance financial inclusion in Kenya.

