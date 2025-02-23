# Subscription Churn Analysis: Understanding Cancellation Trends for Retention Strategy

## Executive Summary  
The company is experiencing a significant churn issue, leading to major revenue loss. Leadership has launched a company-wide retention effort but lacks insights into why customers are canceling their subscriptions. This analysis leverages user-reported cancellation reasons to identify trends, understand pain points, and provide actionable recommendations to improve retention and reduce churn.  

## Business Problem  
High churn rates have negatively impacted revenue, but the company lacks visibility into the root causes. Without clear insights, retention strategies may not effectively address customer concerns. The analytics team has decided to analyze the user-reported cancellation reasons collected during the cancellation workflow to uncover trends and guide strategic decision-making.  

### Key Business Questions  
- What are the most common reasons customers cancel their subscriptions?  
- How do cancellation reasons vary over time?  
- Are there any patterns in user behavior before canceling?  
- What strategies can be implemented to improve retention?  

## Methodology  
1. **Exploratory Data Analysis (EDA)**  
   - Assess data completeness and identify trends in cancellation reasons.  
   - Explore how users interact with the product before canceling.  
2. **Product Funnel Analysis**  
   - Track the cancellation workflow to understand user behavior.  
   - Identify points where rescue tactics could be introduced.  
3. **Data Visualization**  
   - Create bar charts to show the most common cancellation reasons.  
   - Develop trend lines to analyze cancellation reasons over time.  
   - Compare canceled users vs. retained users based on product engagement.  

## Skills Used  
- **SQL**: CTEs, CASE statements, UNION, view creation  
- **Data Wrangling & Cleaning**: Handling missing values, standardizing cancellation reasons  
- **Data Visualization**: Trend analysis, bar charts, user engagement comparisons  
- **Product Analytics**: Identifying user behavior patterns and retention strategies  
- **Snowflake Data Warehouse**: Querying structured datasets  
- **Python (if applicable)**: Pandas, Matplotlib, Seaborn for visualization  

## Results & Business Recommendations  

### Results  
- **X% of users selected at least one additional cancellation reason**, but most did not select all available options, suggesting a lack of interest or frustration with the process.  
- **The top primary cancellation reasons were:**  
  1. Expensive  
  2. Not Useful  
  3. Went to a Competitor  
- **Cancellation reasons have shifted over time**, with an increasing number of users citing “Went to Competitor” in recent months.  

### Business Recommendations  
1. **Improve Onboarding and Support**  
   - Since many users cite "Expensive" and "Not Useful," we should enhance onboarding and provide more guidance early in the subscription. This could help users see the product’s value, making them less price-sensitive.  

2. **Introduce a Discount-Based Retention Offer**  
   - For cost-conscious users, offer a limited-time discount when they initiate cancellation. This could encourage them to stay rather than cancel.  

3. **Competitive Market Analysis**  
   - With “Went to Competitor” being a common secondary reason, we should research competitor offerings to ensure we remain competitive in pricing, features, and user experience.  

4. **Enhance the Cancellation Workflow**  
   - Introduce friction strategically by asking users for feedback in a way that doesn’t increase frustration.  
   - Implement AI-driven exit surveys that suggest alternative plans or discounts based on user behavior.  

## Next Steps  
- **Analyze engagement metrics**: Compare feature usage between ca
