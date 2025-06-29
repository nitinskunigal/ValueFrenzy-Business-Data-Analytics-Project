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
## **Insight 1: Declining Revenue and Gross Profit**

<ins>Insight<ins>: 

The USA contributed the highest revenue (51%) but faced steep declines, driven by reduced high-tier sales and economic challenges. Mexico showed relative resilience, with medium-tier products driving revenue, while Canada, though a smaller market, remained stable, mitigating some overall losses.

✔ Revenue Trends: Total revenue dropped sharply from $13.8M in 2021 to $9.7M in both 2022 and 2023.

✔ Profit Trends: Gross profit followed a similar trend, declining from $8.2M in 2021 to $5.8M in subsequent years.

✔ Category Contributions: Medium-tier products contributed the most to revenue and profit, but high-tier products (electronics and furniture) showed the steepest decline, particularly in the USA.

✔ Regional Performance: Mexico's revenue and profit matched the USA's, showcasing growth potential.

✔ Sales Patterns: Weekday profits totaled $14.1M, outpacing weekend profits of $5.7M, indicating an opportunity to improve weekend sales.

<ins>Root Cause Analysis<ins>: 

✔ Economic Factors: Inflation and economic uncertainty reduced consumer spending on high-value products.

✔ ATV Decline: A sharp drop in Average Transaction Value since Dec 2021 further impacted revenue.

✔ Market Dynamics: USA sales suffered most in high-tier categories, reflecting a need for region-specific strategies.



## **Recommendation 1: Strategies to Address Declining Revenue and Gross Profit**

✔ Revitalize High-Tier Product Sales in the USA:

  - Targeted Promotions: Launch seasonal campaigns during peak shopping periods (e.g., Black Friday, Christmas) to attract customers.

  - Flexible Payment Options: Introduce financing plans such as 0% interest installments to make high-value products more accessible.

✔ Enhance Customer Engagement Across All Regions:

  - Personalized Recommendations: Use customer data to offer tailored suggestions, focusing on medium- and high-tier products.

  - Omnichannel Experience: Strengthen the online shopping experience by integrating exclusive discounts for registered customers.

✔ Boost Weekend Sales:

  - Weekend Promotions: Roll out exclusive discounts or bundle offers during weekends to increase ATV and customer traffic.

  - In-Store Events: Host product demos or flash sales to attract customers.

✔ Leverage Mexico’s Success as a Growth Model:

  - Replicate Mexico’s successful strategies in the USA, particularly for medium-tier products.

  - Expand Mexico’s high-tier product offerings to tap into its market potential.

✔ Tailor Regional Campaigns with Market Research:

  - Develop region-specific marketing campaigns informed by ongoing local market analysis.

  - Adjust product offerings and pricing based on trends to better meet consumer needs.

## **Insight 2: Stable Quantity Sold but Declining Profit Margins**

<ins>Insight<ins>: 

ValueFrenzy maintained a high total sales volume of 15.7 million units, but there were notable shifts in the product mix:

✔ Low-Tier Dominance: Low-tier products (groceries) accounted for 49% of total sales, underscoring their role as a volume driver. However, a decline in sales was observed from Dec-2021 to Jan-2022, likely due to supply chain disruptions and economic pressures.

✔ Medium-Tier Stability: Medium-tier products maintained steady contributions but lacked aggressive growth, particularly in regions like Canada.

✔ High-Tier Challenges: High-tier products, despite having the highest ATV, contributed only 17% of total quantity sold—the lowest among all tiers—highlighting a critical gap in profitability drivers.

<ins>Root Cause Analysis<ins>: 

✔ Economic Constraints: Economic uncertainty led consumers to prioritize essential goods, resulting in a shift towards lower-tier products.

✔ Demand Shift: High-tier products like electronics and furniture saw reduced demand, particularly in the USA, where consumer spending was most affected.

✔ Product Strategy Gaps: Insufficient cross-promotion and bundling strategies for medium- and high-tier products limited their sales potential.

## **Recommendation 2: Optimize Product Mix and Drive High-Tier Sales**

✔ Focus on Medium- and High-Tier Product Growth:

  - Region-Specific Campaigns: In Mexico, emphasize the affordability of premium products by showcasing their quality and durability. In Canada, leverage high-tier product reliability and bundle it with extended warranties or free accessories.

  - Brand Positioning: Reinforce the aspirational value of medium- and high-tier products, positioning them as attainable luxuries that offer long-term benefits.

✔ Leverage Cross-Selling Opportunities:

  - Product Bundles: Design targeted bundles, such as pairing electronics with complementary accessories or offering discounts on household items when purchased with groceries.

  - In-Store and Online Suggestions: Use customer purchase history to recommend high-tier add-ons during low-tier purchases. For example, a customer buying groceries could be offered discounts on small kitchen appliances.

✔ Enhance Marketing and Promotions for High-Tier Products:

  - Run high-tier-focused campaigns during key shopping seasons (e.g., holidays or back-to-school periods).

  - Provide targeted incentives, such as trade-in offers for old electronics or financing options for large purchases.

✔ Monitor Product Performance:

  - Introduce a periodic review of product mix performance to identify early signs of profitability declines.

  - Use regional feedback to refine product offerings and ensure inventory aligns with local customer demand.



## **Insight 3: Disparity Between Transactions and ATV Trends (Oct–Dec)**

<ins>Insight<ins>: 

Transaction volume consistently increased from early October to early December across all three years, particularly during the holiday season. However:

✔ Flat ATV: Despite higher transaction volumes, the Average Transaction Value (ATV) remained stagnant during this period.

✔ Holiday Decline: A sharp ATV drop from over $75 to around $53 occurred between December 2021 and January 2022, reflecting a sustained lower level in 2022 and 2023.

✔ Steady Period Trends: ATV showed minimal fluctuations in non-holiday months, indicating a focus on essentials over discretionary spending.

<ins>Root Cause Analysis<ins>: 

✔ Customer Spending Behavior: Increased transaction volumes were driven by low-tier purchases (groceries), which limited ATV growth.

✔ Economic Constraints: Inflation and reduced disposable income further suppressed spending on high-tier products.

✔ Promotional Gap: Seasonal promotions primarily targeted transaction increases, not ATV growth, limiting the opportunity to capitalize on the holiday surge.

## **Recommendation 3: Boost Average Transaction Value (ATV)**

✔ Implement a Targeted Loyalty Program:

  - Exclusive Rewards for Larger Purchases: Launch a tiered loyalty program offering points for higher spending, with rewards redeemable for medium- and high-tier products.

  - Holiday Promotions: Introduce seasonal rewards, such as bonus points for purchases during the holiday season, to drive both transactions and higher-value sales.

✔ Upselling and Cross-Selling Strategies:

  - Dynamic Suggestions: Use customer purchase history and cart data to suggest premium or complementary products at checkout. Examples: Electronics - Recommend accessories like chargers or screen protectors. Groceries - Suggest related household products, such as bulk cleaning supplies.

  - Bundled Offers: Create bundles that combine high-tier products with frequently purchased low-tier items, offering slight discounts to encourage bulk spending.

✔ Holiday-Specific ATV Campaigns:

  - Personalized Offers: Use targeted marketing emails or app notifications to present curated product bundles or discounts on high-value items during the holiday season.

  - Promotional Financing Options: Offer 0% interest financing or flexible payment plans on high-tier purchases to incentivize larger transactions during key shopping periods.

✔ Monitor and Adjust Campaign Effectiveness:

  - Analyze ATV and transaction data to assess the success of loyalty programs and cross-selling efforts.

  - Use insights to refine offers and adjust strategies for subsequent holiday seasons.

### **Impact of Recommendations**

By incentivizing higher-value purchases and leveraging customer data for targeted upselling, these strategies can:

  - Increase ATV without compromising transaction volumes.

  - Strengthen customer loyalty by offering tangible value through rewards and personalized offers.

  - Align holiday promotions with profitability goals, maximizing the seasonal surge's impact.



## **Insight 4: Impact of Macroeconomic Conditions on Purchasing Patterns**

<ins>Insight<ins>: 

Macroeconomic challenges like inflation, rising operational costs, and shifting customer preferences toward essentials led to fewer high-ticket purchases, particularly electronics. Customers across all regions increasingly opted for value-for-money goods, negatively impacting Average Transaction Value (ATV) and profit margins.

<ins>Root Cause Analysis<ins>: 

✔ Inflationary Pressures: Rising costs of goods and services reduced disposable income, limiting customers' ability to purchase high-value items like electronics and furniture.

✔ Operational Challenges: Increased supply chain costs due to global disruptions further escalated pricing challenges, squeezing profit margins.

✔ Shift in Consumer Preferences: The economic climate prompted a focus on affordable essentials, driving demand for low-cost groceries and private label products.

## **Recommendation 4: Adapt to Macroeconomic Conditions**

✔ Promote Private Label Brands:

  - Highlight private label products as affordable, high-quality alternatives to national brands.

  - Run targeted marketing campaigns to showcase cost savings and value for money, appealing to budget-conscious customers.

✔ Improve Operational Efficiency:

  - Invest in supply chain optimization to reduce operational costs and improve product availability.

  - Implement lean operations and cost-saving measures to maintain competitive pricing without sacrificing profitability.


The insights and root causes show how KPIs are interlinked and affected by economic factors, product tier performance, and regional disparities. The primary focus should be on recovering revenue and profit margins by improving sales in high-margin categories while maintaining steady performance in core product areas like groceries and household goods.

By implementing these data-backed strategies, ValueFrenzy is well-positioned to overcome its current challenges and achieve sustainable growth across all markets.

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
