**Procurement-KPI-Analysis**

How I Found $2.47 Million Hiding in a Procurement Spreadsheet

<img width="1002" height="426" alt="image" src="https://github.com/user-attachments/assets/711c9370-00e8-4fa2-9551-7b640da63348" />

**Introduction**

Every data set has a story to tell and my role as a data analyst is to bring this story to light. When I began working on my “Procurement Performance Tracker” my goal wasn’t to build a mere dashboard but to dive into the “what ““why’s” and “how’s”. What are the underlying issues? Why do they exist? and How can we resolve them? I discovered my dashboard needed to ask the right questions, uncover the important insights and proffer solutions to these problems. 

**Data Story**

This procurement KPI dataset evaluates the efficiency of the e-commerce platform's procurement cycle. By analyzing variables such as order status, delivery timelines, unit pricing, and defect rates, we can better understand how these metrics drive business decisions and determine their outcomes. During my analysis I identified bottlenecks in the supply chain and provided a data driven strategy for the upcoming fiscal year.

**Data Splitting & Preprocessing** 

A clean dataset provides a clear vision. By structuring Independent variables (Supplier, Product category) against Dependent variables (Unit price, Defective unit) I turned raw numbers into a strategic roadmap. I went further to clean the data set by removing duplicates, using Excel built in functions to identify and remove “blanks” within the dataset. I used the excel structured reference to create a new column to show the “gross order value”. I developed a "Procurement Performance Tracker" dashboard to compare vendor reliability and product performance.

<img width="880" height="498" alt="image" src="https://github.com/user-attachments/assets/4754d241-8013-4646-a08f-08a92cf73ec0" />

**Pre- Analysis**

At this stage, I dug deeper. I didn’t just observe the spreadsheet, I looked for the “WHY”.  I asked hard questions as, Which metrics drives profit? What are our star products? “What is our defect rate trend? “Who are our key Suppliers?”. This phase set the tone for the analysis, it helped direct the flow of my project, the visualization, and final output.

**In- Analysis**

Using Excel, I explored the data through pivot table and slicers, I spotted $2.47 Million dollars hiding in lost potential which could be turned into realized revenue and immediately started hunting for the patterns that got us there. Here are the key observations I made: 

•	Under category breakdown: MRO serves as the engine of the operation with 159,030 units sold while Electronics, despite having the lowest price point ($101.34) has the lowest sales despite a 15% lower price point than the category average, sales volume remains low indicating a lack of market penetration rather than a pricing barrier. This suggests that it is not a pricing problem but a visibility issue. 

•	Quality Revolution: In 2023 we hit a peak of 24,767 defects but completely turned it around in 2024 by optimizing our process, the numbers plummeted to just 234 units showing exceptional operational excellence. 

•	Vendor Leaderboard: Here I sought to find our trailblazers, it showed Delta logistics (171 successful deliveries) and Epsilon Group (166 deliveries) are our top guns. Alpha Inc is lagging at 117 deliveries this suggests a need to bring them up to Delta standard. 

What is the game plan? After deriving insights, I went further to provide strategic solutions for these problems, they include
•	Marketing Audit for Electronics: Low sales volume despite low unit pricing suggests a lack of visibility, thus we need to take intentional steps to get it in front of the right eye through targeted marketing, bundle sales and promo offers.

•	Inventory Adjustment: Increase inventory levels for MRO products to ensure the highest-demand category remains in stock and avoids "Out of Stock" scenarios.

•	Cancellation Root-Cause Analysis: With a 10.42% cancellation rate, further investigation is required to determine if cancellations are due to lead times or supplier stockouts.

•	Standardize Quality Protocols: Formally document the quality assurance protocols implemented in 2024 that led to the reduction in defects. This should be the new baseline standard for all vendors to maintain the downward trend.

**Post- Analysis**

During this stage, I discovered a significant misalignment between pricing performance. Raw materials have the highest price points yet ranks 4th in volume, conversely Electronics has the lowest price point yet sits at the bottom of the sales ladder. Thus, this suggests that the barrier to market entry does not lie with affordability but market awareness. Further I deduced that while product quality is solved with the drastic decrease in defective rate in 2024, fulfillment reliability remains the primary bottleneck to scaling evidenced in the 10.42% cancellation rate. This cancellation rate is damaging because it represents sunk costs in processing and customer acquisition without the realized revenue, but reducing this by 5% would yield an estimated 2.47 million dollars increase in realized revenue, significantly impacting the bottom line without additional sales effort. Lastly, there is a 31.5% performance gap between the top vendor (Delta logistics 171) and bottom vendor (Alpha Inc-117). If Alpha Inc. is handling critical components for MRO then their relative underperformance represents a high-risk failure point. 

<img width="583" height="267" alt="image" src="https://github.com/user-attachments/assets/ada61b13-a773-4e20-814b-1fddea068f0b" />

**Data Visualization & Charts**
To effectively communicate insights, I built a dashboard using Excel. The dashboard includes the defect rate yearly trend represented with a line graph to show the defective trend over time, this revealed 2023 had the highest defect rate (24,767), it includes the order fulfillment breakdown represented in a pie chart displaying the data in percentages, It shows the vendor reliability metrics through a bar chart with Delta Logistics taking the lead, It shows the price point comparison by product in a clustered column chart with raw materials being the most expensive product in the pile.  These visualizations make it easier to spot trends quickly, compare performance across board and communicate insights clearly.

**Recommendations**
Based on the procurement performance data and the financial impacts 
identified during analysis, the following strategic actions are recommended:

•	Aggressive Revenue Recovery via Cancellation Management:
The current cancellation rate of 10.42% represents a significant leak in potential earnings. By implementing a "Pre-Shipping Verification" protocol and optimizing warehouse fulfillment speed, a 5% reduction in cancellations would successfully convert approximately $2.47 Million from lost potential to realized revenue.

•	Active Pipeline Management for Pending Orders:
Currently, there are 81 orders (valued at $5.85 Million) sitting in "Pending" status. To prevent these from stagnating and becoming "Cancelled" or "Partially Delivered," I recommend a 48-hour follow-up trigger. Any order remaining pending past 48 hours should be flagged for immediate vendor contact to resolve logistics or stock-count discrepancies.

•	Strategic Marketing and Visibility for Electronics:
Despite Electronics holding the most competitive price point at $103.84, it consistently sits at the bottom of the sales ladder (124,237 units). We should launch a targeted market awareness campaign to address this visibility gap, as the data proves affordability is not the barrier to market penetration.

•	Vendor Performance Improvement Plan (PIP) for Alpha Inc.:
With a reliability score of 141 compared to the lead vendor Delta Logistics (171), Alpha Inc. represents an operational bottleneck. A performance review is recommended to align their fulfillment timelines with Delta’s standards, particularly if they are handling high-volume MRO components.

•	Inventory Scaling for MRO (Operational Engine):
As the highest-performing category by volume (159,030 units), MRO is the backbone of procurement operations. To mitigate the risk of stockouts which contribute to the 10.42% cancellation rate safety stock levels for high-demand MRO items should be increased by 10–15%.

•	Codification of Quality Protocols:
The "Quality Revolution" of 2024, which reduced defects from a peak of 24,767 to just 234 units, must be protected. These quality assurance processes should be formally documented as the new Standard Operating Procedure (SOP) and integrated into all future vendor contracts to maintain this exceptional downward trend.

**Conclusion**

This comprehensive analysis of the Procurement Performance Tracker has evolved from a raw dataset into a powerful strategic roadmap for the organization. By cleaning and structuring the independent variables against delivery outcomes, I have successfully identified the core drivers of procurement efficiency and financial loss.
The most significant finding of this report is the "trapped" revenue within our cancellation pipeline. By following the recommendations to reduce cancellations by just 5%, we can move $2.47 Million from lost potential into realized revenue. Furthermore, by aggressively managing the $5.85 Million currently in the "Pending" category, we secure the company’s cash flow and improve vendor-client trust.
In summary, the transition from 2024 to 2025 should focus on maintaining our high-quality standards while tightening fulfillment logistics. By turning these data-driven insights into action, the procurement department will shift from a cost center to a significant driver of bottom-line growth. The progress of these initiatives can be tracked in real time using the Procurement Performance Tracker dashboard, specifically monitoring the "Order Fulfillment Breakdown" and "Vendor Reliability Matrix" to ensure Alpha Inc. and the Electronics category move toward the target benchmarks.

**References & Appendices**

• Software Used: Microsoft Excel

•	Source: Kaggle



