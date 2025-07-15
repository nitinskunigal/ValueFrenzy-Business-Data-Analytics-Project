# **Section 1: Problem Statement**  
This project analyzes ValueFrenzy, a fictional supermarket chain in the USA, Mexico, and Canada, facing stagnant revenue growth and profitability concerns across regions and product categories. The COO and CFO sought insights into slowing revenue and potential regional inefficiencies or product performance issues.

As the Business Analyst, I examined three years (2021-2023) of sales data, identifying trends affecting revenue, profit, and transaction values. Using Advanced Excel (Power Query, Power Pivot, DAX) and BA techniques (SWOT, Gap Analysis, Stakeholder Interviews, Competitor Benchmarking), I conducted in-depth analysis and created business reports. I developed an interactive dashboard that revealed a 25% drop in Average Transaction Value (ATV) and regional sales disparities.

The ultimate objective was not only to diagnose the root causes of these challenges but also to provide actionable recommendations for revenue recovery and strategies to sustain growth.

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

# **Section 4: Key Performance Indicators & Rationale behind Selected KPIs**

- For this project, I focused on **five Key Performance Indicators (KPIs)** to evaluate ValueFrenzy’s financial and sales performance. **Total Revenue** and **Gross Profit** provided insights into overall earnings and profitability, while **Quantity Sold** and **Total Transactions** helped measure demand and customer activity. Finally, **Average Transaction Value (ATV)** assessed customer spending behavior and pricing effectiveness.
  
- The selection of these KPIs was driven by several factors. First, they aligned with the analysis goals, helping assess business strengths and weaknesses. Second, I prioritized data reliability, ensuring that only complete and high-quality data was used. Some potential metrics, like Return Rate, were excluded due to data gaps.
  
- Additionally, we focused on actionable and clear KPIs to maintain clarity and avoid unnecessary complexity. These metrics also aligned with economic and industry trends, addressing ValueFrenzy’s declining revenue and profitability. While this analysis provided valuable insights, future explorations could incorporate additional metrics such as Customer Retention and Inventory Turnover for a more comprehensive view.

# **Section 5: Key BA Techniques Used**

At the start of the project, I needed to understand ValueFrenzy’s current performance, identify gaps, and uncover strategic opportunities. To achieve this, I applied a structured approach using key business analysis techniques:

- **SWOT Analysis** helped assess ValueFrenzy’s strengths, weaknesses, opportunities, and threats, ensuring that our focus remained on the most critical business priorities.
  
- **Gap Analysis** was used to compare ValueFrenzy’s current (As-Is) state with the desired (To-Be) state. Since we lacked qualitative insights, I leveraged data-driven analysis to identify revenue declines, profitability gaps, and regional performance variations.
  
- **Competitor Benchmarking** provided industry context, helping to evaluate how ValueFrenzy compared to competitors in terms of revenue performance, pricing strategies, and sales trends.
  
- **Process Mapping** played a crucial role in visualizing operational inefficiencies that impacted revenue and ATV. By mapping sales and pricing workflows, I identified areas where process improvements could drive better results.
  
- **Stakeholder Interviews** were conducted with key decision-makers, such as the COO, CFO, and Head of Sales & Marketing, to align the analysis with business objectives. Their inputs helped refine KPI selection and guided the strategic focus.

By combining these techniques, I was able to translate business challenges into data-driven insights, ensuring that the recommendations were both practical and actionable.

# **Section 6: Key Documents Created**
📌 BRD – Defined business & functional requirements, success criteria.

📌 Project Charter – Outlined objectives, scope & stakeholders.

📌 Business Insights & Process Analysis – Included SWOT, Process Flow Diagrams, Gap Analysis, Competitor Benchmarking & Stakeholder Interviews.

📌 Project Report – Consolidated insights & recommendations.

# **Section 7: Key Business Insights**
## **Declining Revenue and Gross Profit:**

![Insights - Total Revenue](https://github.com/nitinskunigal/ValueFrenzy-Business-Data-Analytics-Project/blob/main/Insights%20Screenshots/Insights%20-%20Total%20Revenue.png)

![Insights - Gross Profit](https://github.com/nitinskunigal/ValueFrenzy-Business-Data-Analytics-Project/blob/main/Insights%20Screenshots/Insights%20-%20Gross%20Profit.png)

- Total revenue decreased from $13.8M in 2021 to $9.7M in both 2022 and 2023, with gross profit dropping from $8.2M to $5.8M. The drop was drastic for both revenue and profit between Dec-2021 and Jan-2022.
  
- While there were similar contributions from Low and High-tier products between 2021 and 2023, the medium-tier category contributed maximum towards revenue and profit. Also, Mexico’s contributions are on-par with USA’s contributions and that’s a huge plus for ValueFrenzy.
  
- The core issue was a decline in high-tier sales, particularly in the USA, driven by economic strain, inflation, and a drop in ATV since Dec-2021. Additionally, weekday profits totaled $14.1M, while weekend profits were lower at $5.7M, indicating a need to boost weekend sales.

## **Drop in the Overall Quantity Sold**

![Insights - Quantity Sold](https://github.com/nitinskunigal/ValueFrenzy-Business-Data-Analytics-Project/blob/main/Insights%20Screenshots/Insights%20-%20Quantity%20Sold.png)

- The total quantity sold is high at 15.7 million units, but there has been a significant decline in the overall quantity sold, especially in low-tier products, from Dec-2021 to Jan-2022. Despite its significant decline, low-tier products (groceries) account for 49% of total sales, indicating they drive volume.
  
- Despite having the highest ATV, high-tier products contributed 17% of total quantity sold, which happens to be the lowest amongst three categories, and needs granular attention. This decline was significant as consumers prioritized essential goods over discretionary items.

## **Disparity Between Transactions and ATV Trends (Oct–Dec)**

![Insights - Total Transactions](https://github.com/nitinskunigal/ValueFrenzy-Business-Data-Analytics-Project/blob/main/Insights%20Screenshots/Insights%20-%20Total%20Transactions.png)

![Insights - ATV](https://github.com/nitinskunigal/ValueFrenzy-Business-Data-Analytics-Project/blob/main/Insights%20Screenshots/Insights%20-%20ATV.png)

- Transaction volume remained steady, indicating consistent customer purchases.
  
- However, ATV declined sharply from over $75 in 2021 to around $53 in 2022 and 2023. This suggests more customers were buying lower-value items, resulting in smaller spend per transaction.
  
- The decline in ATV was driven by a shift in customer behavior, with fewer high-value transactions and an increase in low-cost purchases, particularly essentials like groceries. This trend reflects a decrease in customer spending power, influenced by external factors such as inflation.

The insights and root causes show how KPIs are interlinked and affected by economic factors, product tier performance, and regional disparities. The primary focus should be on recovering revenue and profit margins by improving sales in high-margin categories while maintaining steady performance in core product areas like groceries and household goods.


# **Section 8: Business Impact Summary**

Understanding the business impact of our findings was crucial in shaping actionable recommendations.

1. **Revenue Decline & Profitability Challenges:** One of the most significant trends was the decline in both revenue and gross profit post-2021. This pointed to potential pricing inefficiencies and gaps in promotional strategies. While sales continued, margins were shrinking, indicating the need for a more strategic pricing approach.
   
2. **Regional Performance Variances:** Each region displayed unique challenges and opportunities. The USA, our largest market, contributed the most revenue but struggled with profitability. Meanwhile, Mexico maintained steady sales but at lower margins. Interestingly, Canada, despite lower overall sales, had the highest ATV. This indicated an opportunity to leverage premium product strategies in the region.
   
3. **Shifting Customer Behavior:** One of the key behavioral trends was the increase in transaction volume without a corresponding rise in ATV. This suggested that customers were making more frequent but smaller purchases, possibly due to economic constraints or evolving shopping habits. Understanding these shifts was vital for shaping future marketing and pricing strategies.
   
4. **Product Tier Influence:** Revenue was heavily driven by high-tier products, but transaction volumes were primarily fueled by low and mid-tier products. This reinforced the importance of a balanced pricing and inventory strategy—one that maximized high-tier sales while maintaining strong engagement with lower-tier products.
   
5. **Strategic Implications:** Overall, these insights underscored the need for region-specific strategies, dynamic pricing models, and optimized product positioning to enhance revenue and profitability. A one-size-fits-all approach wouldn’t be effective—tailored interventions were necessary to drive sustainable business growth.

# **Section 9: Refining Recommendations Through Stakeholder Collaboration**

Refining our recommendations was not just about analyzing numbers; it was an iterative process shaped by collaboration with key stakeholders to ensure feasibility and real-world impact.

- **Initial Insights & Hypotheses:** Initially, our recommendations were purely data-driven, identifying straightforward correlations, like declining revenue indicating a need for price adjustments. However, business decisions are rarely that simple.
  
- **Stakeholder Feedback & Business Context:** To create strategies that were both practical and impactful, we engaged stakeholders across different functions, including the COO, CFO, Sales, and Product Strategy teams. Their insights revealed critical business realities that raw data alone could not capture.
  
- **Refinement & Finalization:** Through data-driven discussions, our initial hypotheses evolved into actionable, high-impact strategies. Every recommendation was aligned with both business priorities and market realities, ensuring a balance between profitability, customer engagement, and operational feasibility.
  
- **Key Takeaway:** Data alone doesn’t drive decisions; collaborating with stakeholders transforms insights into strategic, real-world solutions.

# **Section 10: Finalized Recommendations for Strategic Growth**

With stakeholder feedback incorporated, we finalized a set of focused, high-impact recommendations aimed at reversing revenue decline, optimizing operations, and strengthening ValueFrenzy’s market position.

- **Refining pricing strategies** became a priority, ensuring adjustments were based on regional spending patterns and product-tier performance. Instead of broad price cuts, we proposed targeted promotions and dynamic pricing strategies to maximize revenue without sacrificing margins.
  
- We also identified the need for **product mix optimization**. High-tier products were the primary revenue drivers, but low and mid-tier products fueled transaction volumes. By realigning inventory and matching regional demand trends, we could ensure efficient stock allocation and improved sales performance.
  
- To **boost transaction value**, we recommended personalized promotions and upselling tactics to encourage customers to spend more per visit. This would increase Average Transaction Value (ATV) without relying solely on price increases.
  
- Another key focus was **leveraging customer insights**. Transactional data could be used to personalize marketing campaigns, improving customer engagement and retention while strengthening brand loyalty.
  
- Finally, **operational efficiency and cost control** were critical. By streamlining supply chain operations and managing COGS effectively, we could maintain profitability without compromising on competitive pricing.

# **Section 11: Rationale Behind Choosing EXCEL as My Go-To Tool**
For this project, I chose Excel as the primary tool for end-to-end data analysis due to its powerful and versatile features:
1.	**Data Processing and Transformation in Power Query**: Enabled efficient data import, cleaning, and transformation, for medium-to-large datasets.

2.	**Data Modeling and DAX in Power Pivot**: Facilitated the creation of a robust data model, integrating fact and dimension tables, while allowing advanced calculations through DAX (Data Analysis Expressions).

3.	**Visualization and Dashboarding**: Offered interactive dashboards with dynamic charts, pivot tables, slicers, and drill-down options, providing an accessible and user-friendly reporting experience.

This project highlights Excel’s potential beyond basic spreadsheet use, showcasing its ability to handle advanced data modeling, in-depth analysis using DAX, and professional-grade reporting, all within a single tool.

# **Section 12: Future Enhancements**
To build on this analysis, future work could include:

**1.	Advanced Visualization**: Using Power BI for real-time, interactive dashboards.
	
**2.	Customer Segmentation Analysis**: Further refining insights based on customer demographics and purchase behavior.
	
**3.	Predictive Modeling**: Applying forecasting techniques to anticipate revenue trends and optimize business strategies.

# **Section 13: Key Takeaways & Lessons Learned**
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

# **Section 14: Conclusion**
This project provided a structured approach to diagnosing ValueFrenzy’s business challenges and opportunities. By integrating data analysis with strategic recommendations, the findings offer a roadmap for improving revenue, optimizing product offerings, and enhancing customer engagement.
By shifting focus from pure analytics to a business-driven perspective, this project reinforces how data-driven decision-making can transform a company’s operational and financial performance.

# **Section 15: View/ Download Project Files**

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
