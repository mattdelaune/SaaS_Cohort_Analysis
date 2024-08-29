# SaaS Customer Segmentation and Cohort Analysis

## Executive Summary
This project conducts a comprehensive cohort analysis to drive insights into customer segmentation, retention, and revenue growth for a SaaS company. By segmenting customers based on first purchase dates and usage patterns, key trends and strategic opportunities were identified.

**Key Insights:**
- **Targeted Customer Segmentation:** Dynamic grouping based on purchase behavior and product usage, leading to precise insights and tailored strategies.
- **Cohort Performance Tracking:** Analysis of retention and revenue over time using CRR, NRR, CLR, and CLV to understand customer behavior and profitability.
- **Strategic Recommendations:** Actionable steps for immediate and long-term growth, with a focus on optimizing customer value.
- **Cost Efficiency:** CLR vs. CLV analysis to identify and prioritize the most profitable segments.
- **Visual Insights:** Effective use of visualizations, such as cohort layer cakes and CLV comparisons, to communicate findings.

**Impact:**
This analysis provides a clear roadmap for enhancing customer retention and maximizing lifetime value, directly supporting strategic decision-making and growth initiatives.

**Demonstrated Skills:**
- **Advanced Data Analysis:** Expertise in uncovering actionable insights from complex datasets.
- **Strategic Business Thinking:** Ability to align data-driven insights with business objectives.
- **Effective Communication:** Clear presentation of data through impactful visuals and concise recommendations.

This project showcases the ability to translate data into strategic actions that drive business success, making it a valuable asset for decision-making in the SaaS industry.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Data Source](#data-source)
- [Business Question](#business-question)
- [Methodology](#methodology)
- [Process](#process)
- [Business Question Specific Insights and Recommendations](#business-question-specific-insights-and-recommendations)
- [General Cohort Analysis Insights and Recommendations:](#general-stakeholder-recommendations)
- [Recommendations for Further Analysis](#future-work)
- [Screenshots/Visual Examples](#screenshots)
- [Conclusion](#conclusion)
- [Contact](#contact)

<a id="technologies-used"></a>

## Technologies Used
- **Anaconda Prompt:** Environment management and package installation.
- **Jupyter Notebooks:** Interactive environment for step-by-step documentation, data cleaning, and analysis.
- **Python:** Core programming language for data analysis, with the following libraries:
	- **Pandas:** Data cleaning and manipulation.
    - **Numpy:** Numerical operations and data manipulation.
	- **Matplotlib & Seaborn:** Data visualization and plotting.
- **Kaggle:** Source of the dataset.
- **Git:** Version control for tracking changes and managing project history, with deployment to GitHub.

<a id="data-source"></a>

## Data Source
[This](https://www.kaggle.com/datasets/nnthanh101/aws-saas-sales) dataset includes customer transaction data from a fictitious SaaS company selling software B2B. The dataset includes columns such as Order ID, Order Date, Customer ID, Product, Sales, and Profit.

<a id="business-question"></a>

## Business Question
**"How effective have recent customer acquisition and engagement strategies been in increasing Customer Lifetime Value (CLV), and what impact do cohort-specific factors, such as promotions and market conditions, have on the financial performance of different customer segments over time?"**

<a id="methodology"></a>

## Methodology
This project conducts a detailed cohort analysis, segmented by first purchase dates and hypothesized product usage groups, to derive actionable insights into **customer engagement**, retention, and revenue generation. Customer segmentation allows us to categorize customers into distinct groups based on their purchasing behavior and product usage, enabling a more tailored analysis of trends and patterns within each segment. **Cohort analysis** is employed as it tracks the performance of these customer segments over time, making it the most effective method to understand how different strategies impact long-term customer value and to identify the factors influencing retention and revenue. This approach is crucial for answering the business question, as it reveals both immediate and evolving customer behaviors that drive profitability.

The analysis focuses on the following key metrics:

- **Customer Retention Rate (CRR):** Measures the percentage of customers within each cohort who continue making purchases over subsequent periods, providing insights into customer loyalty and the effectiveness of retention strategies.
- **Net Revenue Retention (NRR):** Evaluates the percentage of recurring revenue retained from existing customers over a specified period, accounting for upsells, downsells, and churn, offering a comprehensive view of revenue stability and growth.
- **Customer Lifetime Revenue (CLR):** Calculates the total revenue generated by a customer throughout their relationship with the business, helping to identify high-value customer segments.
- **Customer Lifetime Value (CLV):** Estimates the total profit expected from a customer over their entire relationship with the business, guiding strategic decisions on customer acquisition and retention investments.

<a id="process"></a>

## Process
1. **Data and Libraries Import and Loading:** Imported necessary Python libraries, including pandas, numpy, seaborn, and matplotlib. Loaded the dataset containing customer transactions and product details, ensuring all relevant columns were correctly parsed and formatted for analysis.
2. **Exploratory Data Analysis (EDA):** Conducted an initial exploration of the dataset to understand its structure, identify missing values, and detect any anomalies. Generated descriptive statistics and visualizations to gain insights into customer behavior, product performance, and overall sales trends.
3. **Customer Segmentation** Defined products and their respective definitions based on hypothesized usage groups. Segmented the customer base into distinct groups according to these definitions, enabling more targeted analysis of product usage patterns and customer behaviors.
4. **Hypothesized Usage Group Validation:** Validated the hypothesized usage groups through statistical analysis and visualization. Ensured that the segmentation accurately reflected distinct patterns in customer behavior, allowing for more meaningful cohort analysis.
5. **Cohort Analysis:** Performed cohort analysis by calculating and analyzing key metrics such as Customer Retention Rate (CRR), Net Retention Rate (NRR), Customer Lifetime Revenue (CLR), and Customer Lifetime Value (CLV) both overall and within each usage group. Assessed CLR vs. CLV cost efficiency to determine the profitability of each cohort.
6. **Cohort Layer Cake** Created a cohort layer cake visualization to illustrate the cumulative CLV over time, both overall and for each usage group. This visualization helped identify patterns in customer value contribution across different cohorts and highlighted the impact of specific customer acquisition and retention strategies.
7. **Business Question Specifc Insights and Recommendations** Synthesized findings from the EDA, cohort analysis, and cohort layer cake into a cohesive set of results to answer the business question. Identified key trends, insights, and conclusions regarding customer behavior, product performance, and financial outcomes.
8. **General Cohort Analysis Insights and Stakeholdor Recommendations:** Developed actionable recommendations from general insights for stakeholders, segmented into immediate, mid-term, and long-term priorities. These recommendations were prioritized based on their potential impact and urgency, with a focus on enhancing customer engagement, optimizing financial performance, and driving long-term growth.
9. **Recommendations for Further Analysis** Proposed additional analyses to build on the current findings, including churn prediction, advanced customer journey mapping, sentiment analysis, and strategic pricing evaluation. These recommendations aimed to provide deeper insights and support continuous improvement in customer management strategies.

<a id="business-question-specific-insights-and-recommendations"></a>

## Business Question Specifc Insights and Recommendations
1. **Effectiveness of Recent Customer Acquisition and Engagement Strategies:**
- **Observation:** The analysis shows a steady rise in cumulative Customer Lifetime Value (CLV) for newer cohorts, indicating that recent customer acquisition and engagement strategies have been effective. The quick initial rise in CLV for most cohorts underscores strong early engagement and suggests that the strategies employed are successfully attracting and retaining customers in the initial stages.
- **Recommendation:** To maintain and enhance this positive trend, it is recommended to continue focusing on early-stage engagement strategies. Specifically, consider refining onboarding processes, improving the first-touch experience, and offering personalized promotions early in the customer journey. Additionally, leveraging data-driven insights to identify and replicate successful elements of these strategies across all customer segments can ensure consistent results.
2. **Impact of Cohort-Specific Factors on Financial Performance:**
- **Observation:** Variability in growth among different cohorts, especially in mid-2020, suggests that cohort-specific factors such as the timing of customer acquisition campaigns, market conditions, or promotional activities significantly impact the financial performance of customer segments. Some cohorts, particularly from late 2020 and early 2021, exhibited sharp increases in CLV during mid-to-late periods, likely due to effective periodic promotions or re-engagement strategies.
- **Recommendation:** To optimize the financial performance across all cohorts, it's crucial to conduct a detailed analysis of the external and internal factors affecting each cohort. This could involve A/B testing different marketing strategies, timing promotions based on seasonal trends, or tailoring re-engagement strategies to specific customer segments. Additionally, continuously monitor market conditions and adjust acquisition strategies to mitigate potential negative impacts on customer value.
3. **Financial Risk in Specialized Tools and Later Cohorts:**
- **Observation:** The analysis reveals sharp declines and even negative CLV values in some later cohorts, particularly concerning specialized tools. This suggests that certain products or customer segments may be experiencing financial losses or increased costs, potentially due to higher acquisition costs or ineffective engagement strategies in these areas.
- **Recommendation:** To mitigate financial risks, it is recommended to conduct a thorough review of the cost structure and profitability of specialized tools. Implementing tighter cost controls, refining the pricing strategy for these tools, and closely monitoring their performance can prevent further declines. Additionally, identifying underperforming cohorts early and applying targeted interventions can help recover lost value.
4. **Importance of Continuous Customer Acquisition and Retention Efforts:**
- **Observation:** The layer effect observed in the cohort layer cake charts highlights the incremental value brought by each new cohort over time. This underscores the critical importance of maintaining continuous customer acquisition and retention efforts to sustain growth in overall CLV.
- **Recommendation:** To ensure ongoing success, it is recommended to invest in scalable customer acquisition channels and develop robust retention programs that engage customers throughout their lifecycle. This might include loyalty programs, personalized communication, and data-driven insights to predict and prevent churn. Continuously innovating and testing new acquisition and retention strategies will be key to maintaining momentum in CLV growth.
2. **Optimizing Customer Segmentation and Engagement:**
- **Observation:** The cohort analysis emphasizes the value of advanced customer segmentation and targeted engagement strategies. By understanding the unique behaviors and needs of different customer segments, the business can tailor its approach to maximize CLV.
- **Recommendation:** Utilize clustering algorithms and machine learning models to segment customers more effectively based on behavior, preferences, and value. This will enable personalized marketing efforts, improve targeting for retention and upselling campaigns, and ultimately enhance the profitability of each segment. Regularly updating and refining these segments will ensure that marketing efforts remain relevant and effective as customer behaviors evolve.

## General Cohort Analysis Insights and Conclusions:
The analysis demonstrated the effectiveness of recent customer acquisition strategies in driving early engagement and highlighted the importance of ongoing efforts to sustain long-term customer value. While initial strategies were successful, there is a clear need for targeted interventions to address cohort-specific challenges, such as variability in growth and financial performance across different customer segments. To optimize long-term outcomes, the focus should shift to enhancing long-term customer retention, managing financial risks in specialized tools, and continuously adapting acquisition and engagement strategies to changing market conditions.

<a id="general-stakeholder-recommendations"></a>

## General Stakeholder Recommendations:
### Immediate Priorities (High Impact and Urgency)
**Early Engagement and Onboarding**
1. **Integrate Data-Driven Insights:** Leverage cohort analysis findings to fine-tune early engagement strategies, ensuring new customers quickly realize value through personalized onboarding experiences.
2. **Enhance Cross-Selling and Upselling:** Utilize early engagement opportunities to introduce customers to relevant add-ons and upsells, increasing their lifetime value from the outset.
**Promotions and Upselling**
1. **Strategic Timing:** Plan promotions and upselling campaigns based on cohort-specific insights to maximize their impact and address periods of stagnation identified in the analysis.
2. **Targeted Campaigns:** Design marketing campaigns that align with the unique needs of each customer segment, particularly focusing on periods when engagement tends to drop.
### Mid-Term Priorities (High Impact, Lower Urgency)
**Long-Term Engagement and Retention**
1. **Cohort-Specific Retention Strategies:** Develop targeted retention campaigns for cohorts that have shown variability in CLV growth, particularly those impacted by external factors like market conditions.
2. **Ongoing Engagement Touchpoints:** Establish regular, personalized touchpoints to maintain customer interest and address any potential declines in engagement over time.
**Core Services and Long-Term Value**
1. **Sustain Core Value Proposition:** Strengthen the value proposition of core services by continually improving and adapting them based on customer feedback and cohort performance data.
2. **Value-Added Services:** Explore opportunities to introduce new value-added services that align with the evolving needs of long-term customers.
**Cost Efficiency and Data-Driven Strategies**
1. **Financial Performance Monitoring:** Implement continuous financial monitoring to identify and mitigate risks associated with specialized tools or underperforming cohorts.
2. **Personalized Engagement:** Use customer data to develop and refine engagement strategies that are tailored to the specific behaviors and preferences of each customer segment.
### Long-Term Priorities (Lower Impact, Lower Urgency)
**Add-Ons and Plugins**
1. **Bundling Strategies:** Create bundles of core services with relevant add-ons to enhance perceived value and encourage upselling during later stages of the customer journey.
2. **Cohort-Specific Marketing:** Tailor marketing efforts for add-ons to align with the timing and needs of specific cohorts, particularly during periods of reduced engagement.
**Specialized Tools**
1. **Financial Risk Management:** Introduce rigorous financial management practices for specialized tools to minimize losses and enhance profitability.
2. **Highlighting Immediate Benefits:** Adjust marketing and engagement strategies to emphasize the immediate benefits of specialized tools, particularly to cohorts showing early signs of disengagement.
**Continuous Improvement and Monitoring**
1. **Proactive Feedback Collection:** Establish systems to regularly collect and analyze customer feedback, using it to inform ongoing improvements and address emerging issues quickly.
2. **Dedicated Customer Success Teams:** Build a customer success team focused on monitoring key metrics and adapting strategies in real-time to maintain high customer satisfaction and loyalty.

<a id="future-work"></a>

## Recommendations for Further Analysis
To further refine insights and enhance actionable outcomes, consider pursuing the following steps:
1. **Churn Prediction and Root Cause Analysis:** 
- Develop a churn prediction model to proactively identify customers at risk.
- Conduct root cause analysis to understand factors driving churn and develop specific interventions.
2. **Advanced Customer Journey Mapping:** 
- Map out the customer journey in more detail to pinpoint key touchpoints and potential pain points, enabling more targeted engagement strategies.
- Enhance customer engagement at each stage to drive retention and increase long-term value.
3. **Customer Feedback and Sentiment Analysis:** 
- Perform sentiment analysis on customer feedback to identify trends and areas for improvement.
- Establish a continuous feedback loop to ensure customer needs are met and satisfaction remains high.
4. **Strategic Pricing Analysis:** 
- Evaluate current pricing models and discount strategies to optimize revenue and profitability.
- Analyze price sensitivity and elasticity to inform dynamic pricing strategies that align with customer value perceptions.

<a id="screenshots"></a>

## Screenshots/Visual Examples

![CRR](images/cohort_layer_cake_new.png)

![CRR](images/CRR_FirstPurchaseCohort_AddonsPlugins.png)

![CE](images/CostEfficiency_SpecializedTools.png)

![CM](images/Correlation_Matrix.png)

<a id="conclusion"></a>

## Conclusion
This project showcases my ability to perform in-depth cohort analysis and deliver actionable insights that directly impact business strategy and growth. By analyzing customer behavior through segmentation and retention metrics, I identified key opportunities for optimizing customer lifetime value and enhancing overall business performance.

Key takeaways include:
- **Strategic Insight:** The analysis provided clear, data-driven recommendations that align with business goals, focusing on both short-term actions and long-term growth strategies.
- **Analytical Expertise:** Demonstrated proficiency in using advanced data techniques to uncover meaningful trends and patterns, contributing to more informed decision-making.
- **Effective Communication:** Successfully translated complex data into clear, actionable insights, supported by impactful visualizations that convey the story behind the data.
This project exemplifies my commitment to driving business value through data analysis, strategic thinking, and effective communication. I am eager to bring these skills to a dynamic team where I can continue to contribute to data-driven success!

<a id="contact"></a>

## Contact
For more information, please contact:

**Name:** Matt Delaune

**Email:** matt.delaune@gmail.com
