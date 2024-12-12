# SUPPLY CHAIN ANALYSIS REPORT
![Screenshot 2024-12-12 115827](https://github.com/user-attachments/assets/b03cf9f7-bfa7-4b05-ac47-f405503e86db)

## Project Overview
This Supply Chain Analysis Report was meticulously developed as part of my active participation in the Onyx Data November 2024 DataDNA Challenge. The primary objective of this project is to leverage advanced analytics and visualization techniques to gain in-depth insights into various aspects of supply chain management. The analysis focuses on three key areas:

**Performance Overview:** Evaluating critical metrics such as revenue, cost, profit, and production efficiency. This section aims to identify actionable insights that can drive strategic decisions and improve overall operational performance.

**Quality and Production:** Analyzing defect rates, manufacturing costs, and production volumes to highlight areas for process improvement. This part of the report seeks to provide recommendations for enhancing product quality and optimizing production processes.

**Shipping Analysis:** Gaining comprehensive visibility into transportation modes, routes, and logistics performance. The goal here is to identify opportunities for cost and time optimization, thereby improving the efficiency and reliability of the supply chain.

Through this project, I aim to demonstrate my analytical skills and my ability to derive meaningful insights from complex datasets.

## Problem Statement
The supply chain generates a vast amount of data that often remains underutilized, hindering the ability to make data-driven decisions. Key challenges include understanding profitability drivers, identifying defect patterns, and optimizing transportation routes and modes. This project aims to address these challenges by providing a comprehensive analysis of revenue trends, defect rates, lead times, and transportation performance to enhance operational efficiency and support strategic decision-making.

## Process
`Data Preparation (Power Query Editor)`
- The process began with thorough data cleaning, including handling missing values, removing redundant columns, resolving duplicates, and adjusting data types to prepare the dataset for analysis.
  
`DAX Measures`
- Minor measures were created using Data Analysis Expressions (DAX). DAX is a formula language used in Power BI to create custom calculations, aggregations, and metrics.

`Report Creation`
- Using the transformed data from Power Query Editor, a multifaceted Power BI report was created. This report is designed to provide a 360-degree view of the business based on the data.

## Report Previews
### Structure:
The Supply Chain Analysis Report comprises several key sections, each providing unique insights into various aspects of supply chain management:

**Introduction Page:** Serves as a navigation hub with links to other sections within the report.

**Performance Overview:** Evaluates critical metrics such as revenue, cost, profit, and production efficiency to identify actionable insights.

**Quality and Production:** Analyzes defect rates, manufacturing costs, and production volumes to highlight areas for process improvement.

**Shipping Analysis:** Provides visibility into transportation modes, routes, and logistics performance for cost and time optimization.

Feel free to explore each sheet for a deeper understanding of business analytics.

![Screenshot 2024-12-12 123108](https://github.com/user-attachments/assets/02e61f8c-c4ff-4afe-9c52-821b9dda395f)
![Screenshot 2024-12-12 123326](https://github.com/user-attachments/assets/400f137b-47f1-40d6-913d-ef9058c60782)
![Screenshot 2024-12-12 122911](https://github.com/user-attachments/assets/1b9d1e4d-b88a-4c96-a1b6-e36c662a17e9)

**[Click here to access the interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDcyOTgyYmYtNzk0Mi00MmI2LWJlNzMtYzYwODY5NzA0Y2JlIiwidCI6ImY0M2MzMTgyLTcxZjAtNGRjOS04YjA0LTc0OTMwZTNmOGNkYSJ9)** 

## Key Insights

### Financial Performance
- **Revenue and Profitability**: A remarkable total revenue of $578k was achieved, with a cost of $53k, resulting in a substantial total profit of $525k. 
- **Product Sales**: A total of 46k products were sold, with **skincare** contributing 42% of the revenue, followed by **haircare** at 30% and **cosmetics** at 28%.
- **Profitability by Product Type**: I observed that skincare generates the highest revenue and profit. While haircare and cosmetics show potential, slight improvements could drive better results.

### Regional Performance
- **Top Cities**: Mumbai leads in revenue generation, followed by Kolkata and Chennai. Bangalore, despite having the lowest product sales, generated a decent revenue.
- **Improvement Area**: Delhi shows less revenue generation, and Bangalore exhibits the lowest product sales, highlighting opportunities for growth.

### Quality and Production
- **Defect Rates**: I noticed higher defect rates in **haircare** and **skincare** compared to **cosmetics**. Chennai and Kolkata report higher average defect rates across all product types.
- **Production Volume**: Skincare leads production with 43%, followed by haircare at 35% and cosmetics at 12%. There’s a clear trend where increased production volume correlates with higher defect rates.

### Inspection and Stock
- **Inspection Status**: Of all inspections, 36% failed, 23% passed, and 41% remain pending. This points to a need for enhanced quality control processes.
- **Stock Availability**: Haircare and cosmetics have low stock levels, with Delhi particularly needing urgent restocking.

### Shipping and Transportation
- **Transportation Modes**: Road (29%) and rail (28%) dominate transportation usage, followed by air (26%) and sea (17%). Route A is the most used (43%), while Route C is underutilized (20%).
- **Shipping Costs**: The average shipping cost stands at $5.55, with **air** being the highest ($6.02) and **sea** the lowest ($4.97). Road and rail fall in the mid-range.


## Recommendations

### Enhance Product Performance
- I recommend prioritizing **skincare production** while strategizing on enhancing revenue in **haircare** and **cosmetics** by introducing new product lines or promotional offers.
- Focus on optimizing **product quality** in haircare and skincare to reduce defect rates and improve inspection pass percentages.

### Regional Strategies
- Strengthen sales efforts in **Bangalore** and **Delhi** through localized marketing campaigns and targeted promotions.
- Leverage the strong revenue base in Mumbai and Kolkata to introduce high-margin products.

### Quality and Stock Management
- I suggest implementing stricter quality controls in Chennai and Kolkata to lower defect rates.
- Ensure sufficient stock levels for haircare and cosmetics, particularly in **Delhi**, to avoid missed sales opportunities.

### Transportation Optimization
- Consider increasing utilization of **Route C** to balance load distribution and reduce overall shipping costs.
- Optimize transportation modes by increasing the use of cost-effective sea routes while maintaining efficient delivery times.

### Strategic Investments
- Invest in technology for **automated quality control** to reduce inspection failures.
- Enhance production capabilities to manage high volumes without compromising quality, especially for skincare products.

### Actionable Insights
- Use the insights from average shipping costs to negotiate better rates with air and road transport providers.
- Regularly monitor and refine inspection processes to reduce pending rates and ensure timely approvals.

By addressing these key areas, we can drive sustainable growth, enhance customer satisfaction, and boost profitability.

## Challenges and Limitations  

- **Missing Demographics**: The dataset lacked gender, age, and customer segmentation, limiting insights into customer preferences.  
- **No Date Periods**: Absence of time-based data restricted trend analysis and seasonal insights.  
- **Data Imbalance**: Skincare outperformed, while haircare and cosmetics needed improvement, affecting category-wide analysis.  
- **Regional Context**: Missing socioeconomic data for locations hindered deeper regional insights.  
- **Quality Gaps**: High pending inspection rates (41%) limited quality control evaluations.  
- **Stock and Supply Chain**: Lack of real-time stock data made it challenging to address shortages effectively.  
- **Transportation Metrics**: Missing delivery timelines and customer satisfaction data constrained logistics optimization.  

### Suggestions  
- Add demographic and time-period data for targeted and seasonal analysis.  
- Introduce real-time stock monitoring and detailed transportation metrics for supply chain efficiency.  
- Focus on balancing product performance and resolving inspection backlogs.

## Key Learnings  

- **Data Cleaning and Preparation**: Enhanced skills in handling missing values, resolving inconsistencies, and preparing data for analysis.  
- **Data Modeling**: Improved proficiency in creating calculated measures and columns using tools like DAX in Power BI for advanced analytics.  
- **Insight Derivation**: Learned to extract actionable insights from diverse datasets and communicate them effectively.  
- **Visualization Skills**: Developed expertise in designing dashboards that highlight critical business metrics and trends.  
- **Supply Chain Understanding**: Gained an understanding of stock management, transportation efficiency, and their impact on overall performance.  
- **Analytical Thinking**: Strengthened ability to identify patterns, address limitations, and propose data-driven recommendations.  
- **Domain Knowledge**: Acquired insights into the retail and cosmetics industry, including category-wise performance and regional trends.

## Additional Information
- **Cleaned Dataset**: The full cleaned dataset is uploaded in the main section for reference and further analysis.
- **Interactive Dashboard**: You can access the interactive dashboard through the link provided in the 'Dashboard' section of this README file.

## Tech Stack
Project relies on the following key technologies:

- `Power BI Desktop` Design, visualization, and interactive reporting.
- `DAX (Data Analysis Expressions)` Creation of calculations and measures supporting data visualizations.
- `Power Query` Clean and transform raw data into a structured format.

## License
This project is licensed under the MIT License, allowing you to use, modify, and distribute the code and visuals while maintaining the original license terms.

---

For questions or feedback, please contact: ajaysonkatar@gmail.com

Enjoy exploring the project!

