# 📊 Subscription Cancelation Analysis

## Executive Summary
The company is experiencing a retention crisis: customers are signing up for subscriptions but are increasingly choosing to cancel rather than renew. The CEO and leadership team are alarmed by rising churn and demand a clear explanation before the next board meeting.  

This project analyzes cancelation workflow data to uncover why customers are leaving, validate whether the data is complete and reliable, and generate actionable recommendations to improve retention.  

---

## Business Problem
- High churn rate is reducing recurring revenue and worrying leadership.  
- Customers are required to select at least one reason when canceling, with the option to provide up to two additional reasons.  
- Key questions:  
  - Are customers providing meaningful data in these dropdowns?  
  - What are the most common reasons for cancelation?  
  - Do primary, secondary, and tertiary reasons differ in patterns?  
  - How can the company use these insights to increase retention?  

---

## Methodology
1. **Cancelation Flow Review** – Worked with the product manager to understand the workflow and how data is logged.  
2. **Data Quality Check** – Verified completeness of cancelation reasons (Reason 1 required, Reason 2 and 3 optional).  
3. **Trend Analysis** – Explored cancelation reasons over time (2022–2024).  
4. **Breakdown by Reason Level** – Compared most common primary, secondary, and tertiary selections.  
5. **Visualization** – Built line charts and bar charts to identify trends, relative frequencies, and data coverage.  

---

## Skills Demonstrated
- SQL querying and data cleaning  
- Funnel and categorical analysis  
- Data visualization and trend analysis  
- Business problem framing and stakeholder communication  

---

## Results & Findings

### Data Completeness
- Nearly all cancelations included a primary reason.  
- A significant share also provided secondary and tertiary reasons, suggesting customers are genuinely sharing insights rather than rushing through.  

### Cancelation Drivers
- **Top primary reasons:**  
  - *Went to a competitor* (most common)  
  - *Expensive* (second most common)  
- **Secondary/Tertiary reasons** reinforce these same themes, with added mentions of *Not useful* and *Bad customer service*.  
- **Consistency across levels** shows the data is reliable and repeatable.  

### Trends Over Time
- Cancelation reasons have remained consistent from 2022–2024.  
- Slight increase in **“Expensive”** → suggests rising price sensitivity.  
- **“Went to a competitor”** dominates → customers still value the category but find better alternatives elsewhere.  

---

## Visualizations

> Replace placeholders below with actual chart image links stored in your repo’s `/images/` folder.  

- Cancelation Reasons Over Time  
  ![Cancelation Trends](images/cancelation_trends.png)  

- Distribution of Primary, Secondary, Tertiary Reasons  
  ![Cancelation Breakdown](images/cancelation_breakdown.png)  

- Reason 1 by Category  
  ![Reason 1](images/cancelation_reason1.png)  

- Reason 2 by Category  
  ![Reason 2](images/cancelation_reason2.png)  

- Reason 3 by Category  
  ![Reason 3](images/cancelation_reason3.png)  

---

## Business Recommendations
1. **Competitive Benchmarking** – Identify why competitors are winning and emphasize differentiators in marketing and product development.  
2. **Pricing Strategy** – Test alternative pricing models (discounts, loyalty rewards, flexible tiers) to reduce cost-driven churn.  
3. **Product Stickiness** – Increase perceived usefulness through onboarding improvements, education campaigns, and usage nudges.  
4. **Customer Support Enhancements** – Address dissatisfaction with proactive service improvements.  

---

## Next Steps
- Build a **dashboard** to continuously monitor churn reasons.  
- Enrich cancelation data by integrating **qualitative feedback** from customer support with categorical dropdown data.  
- Partner with **product and marketing teams** to test retention experiments (pricing pilots, feature adoption campaigns, support SLAs).  
- Present findings to leadership with projected **revenue impact** of addressing churn drivers.  

---

✨ **Takeaway:** Cancelation analysis clearly shows churn is primarily driven by **competition and pricing**. Addressing these pain points through **better differentiation, pricing experiments, and improved customer experience** will directly reduce churn and protect long-term revenue.  


https://app.hex.tech/big-sql-energy/app/Subscription-Cancelation-Analysis-1n9TRT1YHxfCuHCkpxrQyu/latest
