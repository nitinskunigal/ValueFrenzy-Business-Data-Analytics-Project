# **Section 1: Project Overview**  
This project serves as a comprehensive business analysis for ValueFrenzy, a fictional supermarket chain specializing in Retail and Consumer Goods products across the USA, Mexico, and Canada. With a focus on diagnosing critical business challenges, the project examines key performance metrics—Total Revenue, Gross Profit, Quantity Sold, Total Transactions, and Average Transaction Value (ATV)—to uncover actionable insights and strategic recommendations for sustainable growth.
Leveraging historical sales data from 2021 to 2023, the analysis explores performance trends across regions and product categories (low-tier groceries, medium-tier household goods, and high-tier electronics). The primary objective is to address significant revenue and profitability declines in the USA market, identify root causes, and propose targeted strategies to enhance ValueFrenzy's competitive positioning and operational efficiency.
  
The objective of this project is to assist ValueFrenzy in understanding sales trends from 2021-2023, identify the root causes of declining revenue and profitability, and provide actionable insights and recommendations to improve operational efficiency and market competitiveness across its three regions: USA, Mexico, and Canada.

# **Section 2: Motivation**  
The Retail and Consumer Goods industry is characterized by intense competition, evolving customer preferences, and thin profit margins. For a supermarket chain like ValueFrenzy, sustaining profitability while adapting to these dynamic market conditions is critical. This project was motivated by the need to analyze historical performance trends, identify operational and strategic gaps, and uncover opportunities for growth.
By addressing key challenges such as declining revenue in the USA and shifting customer behaviors across regions, the project seeks to equip ValueFrenzy with actionable insights to enhance decision-making, improve customer satisfaction, and maintain its competitive edge in the Retail and Consumer Goods landscape.

# **Section 3: Data Sources**
The dataset used for this analysis consisted of historical sales data spanning the years 2021-2023, provided in CSV format. This eliminated the need for database queries or SQL-based data retrieval. Instead, the data was directly imported into Power Query for cleaning, transformation, and modeling, ensuring a streamlined and efficient data preparation process.
The dataset captured critical metrics, including sales transactions, product categories, and regional performance, which were essential for deriving actionable insights and aligning recommendations with ValueFrenzy’s business goals.

# **Section 4: Data Model**

The data model for this project was meticulously crafted using Power Pivot, establishing robust relationships between the fact table (sales data) and dimension tables (products, regions, and time periods). Serving as the analytical backbone, the data model enables seamless integration of complex calculations and dynamic insights. It facilitates multi-dimensional data slicing and trend analysis, providing a solid foundation for actionable recommendations. The relationships are structured as follows:

![ValueFrenzy Data Model](https://github.com/user-attachments/assets/f95401f3-dde9-4cc9-a792-837262b9d0c0)
 
## ***Fact Table (Sales):***
Consolidates sales transaction data (2021–2023) segmented by region, product category, and time.
## ***Dimension Tables:***
### *Products:* 
Classifies products into three tiers—low-tier (groceries), medium-tier (household goods), and high-tier (electronics).
### *Regions:* 
Includes data for ValueFrenzy’s operational regions—USA, Mexico, and Canada.
### *Calendar:* 
Segments data by year, quarter, and month to enable granular trend analysis.

If you want to take a sneak-peak into the Excel Dashboard, do check out the [Excel Dashboard Walkthrough Video Presentation](https://vimeo.com/1017520699/1e8d13e93d)

# **Section 5: Key KPIs**

## **Total Revenue**
•	 Measures the overall income generated across all regions (USA, Mexico, and Canada) and product categories.

•	 Purpose: To evaluate regional revenue contributions, identify trends, and assess the impact of strategic decisions on overall income.

## **Gross Profit**
•	Calculated as Total Revenue minus the Cost of Goods Sold (COGS).

•	Purpose: To provide insights into the profitability of products and regions, guiding decisions on cost management and margin optimization.

## **Quantity Sold**
•	Represents the total units sold across all regions and product tiers (low, medium, and high).

•	Purpose: To analyze product performance, demand trends, and the effectiveness of sales strategies.

## **Total Transactions**
•	The total number of customer transactions processed across all regions.

•	Purpose: To understand customer activity and engagement levels, and their impact on revenue generation.

## **Average Transaction Value (ATV)**
•	The average value of a single transaction, calculated as Total Revenue divided by Total Transactions.

•	Purpose: To gauge customer spending behavior, identify opportunities for upselling, and align pricing strategies with market demand.

# **Section 6: Insights and Recommendations**
The detailed insights and actionable recommendations derived from this project are comprehensively documented in the project report. This includes:

•	Root cause analysis of declining revenue and profitability.

•	Regional and product-tier-specific performance trends.

•	Strategies to enhance operational efficiency and customer satisfaction.

For a more detailed look at the insights and recommendations, please refer to the [Project Report](https://github.com/nitinskunigal/Vision360-Business-Analysis-Project/blob/main/Project%20Report.pdf) and the [Project Presentation Slides](https://github.com/nitinskunigal/Vision360-Business-Analysis-Project/blob/main/Project%20Presentation.pdf).

# **Section 7: Rationale Behind Choosing EXCEL as My Go-To Tool**
For this project, I chose Excel as the primary tool for end-to-end data analysis due to its powerful and versatile features:
1.	**Data Processing and Transformation in Power Query**: Enabled efficient data import, cleaning, and transformation, for medium-to-large datasets.

2.	**Data Modeling and DAX in Power Pivot**: Facilitated the creation of a robust data model, integrating fact and dimension tables, while allowing advanced calculations through DAX (Data Analysis Expressions).

3.	**Visualization and Dashboarding**: Offered interactive dashboards with dynamic charts, pivot tables, slicers, and drill-down options, providing an accessible and user-friendly reporting experience.

This project highlights Excel’s potential beyond basic spreadsheet use, showcasing its ability to handle advanced data modeling, in-depth analysis using DAX, and professional-grade reporting, all within a single tool.

# **Section 8: How to Use This Project**
While this project provides valuable insights, there are several ways it can be expanded:

1.	Scaling Up: Integrate advanced tools like Power BI for more sophisticated visualizations and enhanced interactivity, particularly when working with extremely large and complex datasets.
	
2.	Deeper Analysis: Further segment the data by product categories, customer demographics, and micro-markets to obtain more granular insights for targeted strategies.
	
3.	Predictive Analytics: Implement machine learning models to forecast future sales trends, customer behaviors, and potential revenue, allowing for data-driven decision-making.

# **Section 9: Future Work / Next Steps**
While this project provides valuable insights, there are several ways it can be expanded:

1.	Scaling Up: Integrate more advanced data tools like Power BI for enhanced visualizations and interactivity, especially for larger datasets.

2.	Deeper Analysis: Further segment the data by product categories, customer demographics, and geographic micro-markets to gain more granular insights.

3.	Predictive Analytics: Use machine learning models to forecast future sales trends, customer behavior, and revenue potential.

# **Section 10: Lessons Learned**
Working on the ValueFrenzy data analysis project has provided invaluable insights from various business and analytical perspectives:

## ***1. Data Preparation and Cleaning:***
The importance of robust data preparation and cleaning cannot be overstated in any business analysis. Dealing with incomplete and inconsistent data required a deep dive into Power Query for automated cleaning processes. This taught me how to effectively resolve data quality issues and ensure accurate, reliable data for analysis.

## ***2. Working with Real-World Business Data:***
The ability to contextualize data according to business logic—such as segmenting by product tiers and regions—was a crucial lesson. Understanding the underlying business rules and objectives helped refine data transformations and ensured that the analysis aligned with business priorities, enhancing the decision-making process.

## ***3. Defining Key Metrics and KPIs:***
Identifying and tracking the right KPIs (Total Revenue, Gross Profit, Quantity Sold, Total Transactions, and Average Transaction Value) highlighted the importance of aligning analytical efforts with business goals. It reinforced the need to communicate clearly how these KPIs impact business performance and strategic decisions.

## ***4. Data Modeling and DAX Measures in Power Pivot:***
Setting up an effective data model (skeleton) upfront, before loading data into Power Query, proved crucial for efficient querying and analysis. This approach helped optimize performance and allowed for more dynamic reporting through DAX measures and reinforced the importance of data normalization and having well-defined data relationships. Structuring the model carefully and using different DAX measures ensured that I could analyze data in ways that directly addressed business questions—linking all KPIs seamlessly, something not easily achieved with simple pivot tables.

## ***5. Dashboard Design and Presentation:***
Creating a dashboard that effectively conveyed business insights was a valuable lesson in visual communication. Balancing aesthetics with functionality—ensuring key business insights were presented in an easy-to-understand, accessible format—helped me refine my skills in visual storytelling. A well-designed dashboard enables decision-makers to quickly grasp important trends and make informed decisions.

## ***6. Stakeholder Collaboration and Feedback:***
Working through feedback loops with hypothetical stakeholders, such as Sarah (COO), emphasized the importance of engaging stakeholders early and often in the analysis process. The ability to adjust my analysis and recommendations based on feedback, especially from a business-oriented perspective, reinforced the value of a collaborative, iterative approach in business analysis.

## ***7. Time Management and Agile Approach:***
Managing the project in sprints and delivering results incrementally taught me the value of flexibility and adaptability in meeting evolving business needs. Whether gathering data, analyzing trends, or presenting insights, I learned to prioritize tasks and maintain a balance between strategic goals and tight timelines.

Overall, this project was a comprehensive learning experience, covering everything from technical data handling to strategic business analysis and communication. It has prepared me well for future business analysis projects where technical skills, business understanding, and stakeholder engagement all converge.

# **Section 11: Conclusion**
This project has provided a comprehensive analysis of ValueFrenzy’s sales performance across its key markets: the USA, Mexico, and Canada. By analyzing KPIs like Total Revenue, Gross Profit, Quantity Sold, and Average Transaction Value (ATV), we were able to uncover critical insights into declining revenue and profitability. The findings suggest that a combination of product segmentation, regional variations, and customer behavior are driving these trends.
Key recommendations include focusing on targeted marketing efforts, revisiting product pricing strategies, and leveraging data-driven decision-making to optimize operations. The project has reinforced the importance of aligning data analysis with business goals and demonstrated how Excel can be a powerful tool for both technical analysis and presenting actionable business insights.

# **Section 12: View/ Download Project Files**

•	[Business Case (PDF)](https://github.com/nitinskunigal/Vision360-Business-Analysis-Project/blob/main/Business%20Case.pdf)

• [Project Charter (PDF)](https://github.com/nitinskunigal/Vision360-Business-Analysis-Project/blob/main/Project%20Charter.pdf)

• [Project Report (PDF)](https://github.com/nitinskunigal/Vision360-Business-Analysis-Project/blob/main/Project%20Report.pdf)

•	[Presentation Slides (PDF)](https://github.com/nitinskunigal/Vision360-Business-Analysis-Project/blob/main/Project%20Presentation.pdf)

•	[Project Presentation (Video) - Strategic Level](https://vimeo.com/1017163715/5b8ede65e1)

•	[Excel Dashboard Walkthrough Video Presentation](https://vimeo.com/1017520699/1e8d13e93d)

# Note: 
Screenshots of the ValueFrenzy multi-page dashboard are available in this repository. For those interested in exploring the interactive Excel version, feel free to reach out to me, and I’d be happy to provide access.
