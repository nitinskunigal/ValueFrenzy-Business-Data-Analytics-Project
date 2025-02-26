# **Section 1: Project Overview**  
The earlier version of ValueFrenzy project primarily focused on data analysis—uncovering sales trends, transaction patterns, and pricing inefficiencies. But business decisions aren’t just about data; they require strategic alignment, stakeholder insights, and business context. That’s why I enhanced this project—integrating Business Analysis (BA) techniques to drive actionable solutions. This project presents a business analysis of ValueFrenzy, a fictional supermarket chain across the USA, Mexico, and Canada. 

The analysis aims to diagnose critical business challenges, particularly declining revenue and profitability in the USA, while exploring key performance metrics—Total Revenue, Gross Profit, Quantity Sold, Total Transactions, and Average Transaction Value (ATV). The project’s core objective is to provide actionable insights and strategic recommendations that enhance ValueFrenzy's market positioning, operational efficiency, and customer engagement.

Using historical sales data from 2021 to 2023, the analysis identifies regional trends, product performance, and customer behavior to help ValueFrenzy make data-driven business decisions. By addressing key issues such as profitability erosion, shifts in consumer demand, and regional performance disparities, this project enables ValueFrenzy to refine its business strategy for sustainable growth.

# **Section 2: Motivation**  
The Retail and Consumer Goods industry operates in a highly competitive and rapidly evolving market environment. Supermarkets like ValueFrenzy face challenges such as changing customer preferences, fluctuating costs, and competitive pricing pressures. This project was motivated by the need to:

✅ Understand why ValueFrenzy is experiencing a decline in revenue and profitability in the USA.

✅ Identify trends in customer spending habits across different regions and product categories.

✅ Provide data-backed recommendations to improve operational efficiency, pricing strategies, and customer satisfaction.

✅ Support strategic decision-making through business-driven insights rather than purely numerical analysis.


# **Section 3: Data Sources**
The analysis is based on historical sales data from 2021-2023, available in CSV format. The data includes sales transactions, product categories, and regional performance metrics. To prepare the data for analysis:

✅ Power Query was used for data cleaning and transformation.

✅ Power Pivot was utilized to establish relationships between sales data (fact table) and relevant business dimensions (products, regions, and time).

✅ No SQL queries were required, as all transformations were performed within Excel’s ecosystem.

# **Section 4: Key KPIs**

## **Total Revenue**
✔ Measures the overall income generated across all regions (USA, Mexico, and Canada) and product categories.

✔ Purpose: To evaluate regional revenue contributions, identify trends, and assess the impact of strategic decisions on overall income.

## **Gross Profit**
✔ Calculated as Total Revenue minus the Cost of Goods Sold (COGS).

✔ Purpose: To provide insights into the profitability of products and regions, guiding decisions on cost management and margin optimization.

## **Quantity Sold**
✔ Represents the total units sold across all regions and product tiers (low, medium, and high).

✔ Purpose: To analyze product performance, demand trends, and the effectiveness of sales strategies.

## **Total Transactions**
✔ The total number of customer transactions processed across all regions.

✔ Purpose: To understand customer activity and engagement levels, and their impact on revenue generation.

## **Average Transaction Value (ATV)**
✔ The average value of a single transaction, calculated as Total Revenue divided by Total Transactions.

✔ Purpose: To gauge customer spending behavior, identify opportunities for upselling, and align pricing strategies with market demand.

# **Section 5: Key BA Techniques Used**

✅ SWOT & Gap Analysis – Assessed internal inefficiencies and competitive positioning.

✅ Process Mapping – Mapped inventory & checkout workflows to streamline operations.

✅ Stakeholder Interviews – Engaged the COO, CFO, and key department heads to align insights with business strategy.

✅ Competitor Benchmarking – Evaluated market trends and industry best practices to refine recommendations.

# **Section 6: Key Documents Created**
📌 Business Case – Justified project viability, expected ROI.

📌 BRD – Defined business & functional requirements, success criteria.

📌 Project Charter – Outlined objectives, scope & stakeholders.

📌 Business Insights & Process Analysis – Included SWOT, Process Flow Diagrams, Gap Analysis, Competitor Benchmarking & Stakeholder Interviews.

📌 Project Report – Consolidated insights & recommendations.

# **Section 7: Business Insights and Recommendations**
## **1. Revenue and Profitability Trends**

✔ ***Observation***: The USA, which accounts for 51% of total revenue, has seen a significant decline in revenue and gross profit since late 2021.

✔ **Key Drivers**: Lower customer spending, changes in product mix, and reduced transaction volume.

✔ **Recommendation**: Implement targeted promotions, optimize product pricing, and reassess high-cost SKUs to improve margins.

## **2. Regional Performance Comparison**

✔ **Observation**: While the USA has struggled, Mexico has maintained relatively stable revenue, and Canada, despite lower total sales, has the highest Average Transaction Value (ATV).

✔ **Recommendation**: Leverage successful pricing and product bundling strategies from Mexico and Canada to address performance gaps in the USA.

## **3. Product Category Insights**

✔ **Observation**: High-tier electronics contribute the most to revenue but have fluctuating demand, while low-tier groceries drive consistent sales volume.

✔ **Recommendation**: Focus on demand forecasting to ensure optimal inventory levels and pricing adjustments for high-value products.

## **4. Customer Behavior & Transactions**

✔ **Observation**: Transaction volume increased in late 2021 but did not translate into higher ATV, suggesting discount-driven sales.

✔ **Recommendation**: Introduce loyalty programs and targeted upselling strategies to improve customer retention and increase per-transaction spending.

# **Section 8: Rationale Behind Choosing EXCEL as My Go-To Tool**
For this project, I chose Excel as the primary tool for end-to-end data analysis due to its powerful and versatile features:
1.	**Data Processing and Transformation in Power Query**: Enabled efficient data import, cleaning, and transformation, for medium-to-large datasets.

2.	**Data Modeling and DAX in Power Pivot**: Facilitated the creation of a robust data model, integrating fact and dimension tables, while allowing advanced calculations through DAX (Data Analysis Expressions).

3.	**Visualization and Dashboarding**: Offered interactive dashboards with dynamic charts, pivot tables, slicers, and drill-down options, providing an accessible and user-friendly reporting experience.

This project highlights Excel’s potential beyond basic spreadsheet use, showcasing its ability to handle advanced data modeling, in-depth analysis using DAX, and professional-grade reporting, all within a single tool.

# **Section 9: Future Enhancements**
To build on this analysis, future work could include:

**1.	Advanced Visualization**: Using Power BI for real-time, interactive dashboards.
	
**2.	Customer Segmentation Analysis**: Further refining insights based on customer demographics and purchase behavior.
	
**3.	Predictive Modeling**: Applying forecasting techniques to anticipate revenue trends and optimize business strategies.

# **Section 10: Key Takeaways & Lessons Learned**
Working on the ValueFrenzy data analysis project has provided invaluable insights from various business and analytical perspectives:

## ***1. Data Preparation and Cleaning:***
The importance of robust data preparation and cleaning cannot be overstated in any business data analytics. Dealing with incomplete and inconsistent data required a deep dive into Power Query for automated cleaning processes. This taught me how to effectively resolve data quality issues and ensure accurate, reliable data for analysis.

## ***2. Working with Real-World Business Data:***
The ability to contextualize data according to business logic—such as segmenting by product tiers and regions—was a crucial lesson. Understanding the underlying business rules and objectives helped refine data transformations and ensured that the analysis aligned with business priorities, enhancing the decision-making process.

## ***3. Defining Key Metrics and KPIs:***
Identifying and tracking the right KPIs (Total Revenue, Gross Profit, Quantity Sold, Total Transactions, and Average Transaction Value) highlighted the importance of aligning analytical efforts with business goals. It reinforced the need to communicate clearly how these KPIs impact business performance and strategic decisions.

## ***4. Data Modeling and DAX Measures in Power Pivot:***
Setting up an effective data model (skeleton) upfront, before loading data into Power Query, proved crucial for efficient querying and analysis. This approach helped optimize performance and allowed for more dynamic reporting through DAX measures and reinforced the importance of data normalization and having well-defined data relationships. Structuring the model carefully and using different DAX measures ensured that I could analyze data in ways that directly addressed business questions—linking all KPIs seamlessly, something not easily achieved with simple pivot tables.

## ***5. Dashboard Design and Presentation:***
Creating a dashboard that effectively conveyed business insights was a valuable lesson in visual communication. Balancing aesthetics with functionality—ensuring key business insights were presented in an easy-to-understand, accessible format—helped me refine my skills in visual storytelling. A well-designed dashboard enables decision-makers to quickly grasp important trends and make informed decisions.

## ***6. Stakeholder Collaboration and Feedback:***
Working through feedback loops with hypothetical stakeholders, such as Sarah (COO), emphasized the importance of engaging stakeholders early and often in the analysis process. The ability to adjust my analysis and recommendations based on feedback, especially from a business-oriented perspective, reinforced the value of a collaborative, iterative approach in business data analytics.

## ***7. Time Management and Agile Approach:***
Managing the project in sprints and delivering results incrementally taught me the value of flexibility and adaptability in meeting evolving business needs. Whether gathering data, analyzing trends, or presenting insights, I learned to prioritize tasks and maintain a balance between strategic goals and tight timelines.

Overall, this project was a comprehensive learning experience, covering everything from technical data handling to strategic business data analytics and communication. It has prepared me well for future business analysis projects where technical skills, business understanding, and stakeholder engagement all converge.

# **Section 11: Conclusion**
This project provided a structured approach to diagnosing ValueFrenzy’s business challenges and opportunities. By integrating data analysis with strategic recommendations, the findings offer a roadmap for improving revenue, optimizing product offerings, and enhancing customer engagement.
By shifting focus from pure analytics to a business-driven perspective, this project reinforces how data-driven decision-making can transform a company’s operational and financial performance.

# **Section 12: View/ Download Project Files**

• [Business Case (PDF)](https://github.com/nitinskunigal/ValueFrenzy-Business-Analysis-Project/blob/main/Business%20Case.pdf)

• [Business Requirements Document (BRD) (PDF)](https://github.com/nitinskunigal/ValueFrenzy-Business-Analysis-Project/blob/main/Business%20Requirements%20Document%20(BRD).pdf)

• [Project Charter (PDF)](https://github.com/nitinskunigal/ValueFrenzy-Business-Analysis-Project/blob/main/Project%20Charter.pdf)

• [Business Insights & Process Analysis (PDF)](https://github.com/nitinskunigal/ValueFrenzy-Business-Analysis-Project/blob/main/Business%20Insights%20%26%20Process%20Analysis.pdf)

• [Process Flow Diagrams (PDF)](https://github.com/nitinskunigal/ValueFrenzy-Business-Analysis-Project/blob/main/Process%20Flow%20Diagrams.pdf)

• [Project Report (PDF)](https://github.com/nitinskunigal/Vision360-Business-Analysis-Project/blob/main/Project%20Report.pdf)

• [Presentation Slides (PDF)](https://github.com/nitinskunigal/ValueFrenzy-Business-Analysis-Project/blob/main/Project%20Presentation.pdf)

• [Project Presentation (Video)](https://vimeo.com/1060217577/b759d7e0de)

• [Excel Dashboard Walkthrough Video Presentation](https://vimeo.com/1017520699/1e8d13e93d)

# Note: 
Screenshots of the ValueFrenzy multi-page dashboard are available in this repository. For those interested in exploring the interactive Excel version, feel free to reach out to me, and I’d be happy to provide access.
