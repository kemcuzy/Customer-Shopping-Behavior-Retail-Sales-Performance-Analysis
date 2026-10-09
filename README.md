# Customer-Shopping-Behavior-Retail-Sales-Performance-Analysis
This project analyzes 99,457 retail transactions to understand customer behaviour, revenue performance, product categories, payment methods, shopping-mall performance and sales trends.  

The project was completed using Microsoft Excel, with a strong focus on transforming transactional data into business-focused insights.  
  
 
 Industry: Retail / Consumer Goods: Microsoft Excel
 
 Analysis approach: Data Cleaning → Pre-Analysis → In-Analysis → Post-Analysis
 
 Dataset: Customer shopping transaction data

 Primary objective: Understand customer behaviour, purchasing patterns, product pricing, sales performance and shopping-mall performance to support better retail decisions.

1. Executive Summary

Retail businesses generate large volumes of transactional data, but raw transactions alone do not immediately reveal who the most valuable customers are, what customers purchase, how they pay, which locations generate the most revenue, or how sales change over time.
This project analyzes a customer shopping dataset containing 99,457 transactions/customers across different product categories, shopping malls, payment methods, genders and age groups.

The analysis generated several important findings:


Total Revenue: $251.51M

Total Orders: 99,457

Unique Customers: 99,457

Average Transaction Value: approximately $2,528.91

Highest-revenue age group: Middle Age — $98.40M

Highest-revenue shopping mall: Mall of Istanbul — $50.87M

Highest total price category: Clothing — $31.08M

Most-used payment method by quantity: Cash

Highest average unit price: Technology — $1,050

Highest sales year: 2022 — $115.44M

The analysis also reveals an important data-quality/business interpretation issue: 

2023 revenue is considerably lower than 2021 and 2022, but this should not automatically be interpreted as a business collapse until the completeness of the 2023 reporting period is validated.
That is an important example of applying analytical thinking rather than simply reading a chart.


2. Business Problem

The business has transactional customer data but needs to transform the data into actionable business intelligence.

Management needs answers to questions such as:

Who contributes most to revenue?

Which customer age group generates the most sales?

Which product categories carry the greatest price value?

Which shopping malls generate the highest revenue?

Which payment method is most commonly used?

Are purchasing patterns different between male and female customers?

How has revenue changed over time?

The purpose of the analysis is therefore to move from:

Raw Transactions → Information → Insights → Actionable Business Decisions


3. Project Objectives

The analysis was designed to:

Determine total revenue generated.

Determine the number of transactions/orders.

Identify unique customers.

Calculate Average Transaction Value.

Analyze revenue by age group.

Evaluate product category performance.

Identify the most-used payment method.

Identify the highest-performing shopping malls.

Examine purchasing patterns by gender.

Analyze the sales trend across years.

Compare average unit prices across product categories.

Identify opportunities for improving revenue and customer engagement.


4. Data Preparation

The original dataset contained fields including:


Invoice Number

Customer ID

Gender

Age

Category

Quantity

Price

Invoice Date

Shopping Mall

Age Group

Revenue

Unit Price

Payment Method

Additional analytical fields such as Age Group and Year were incorporated to make the dataset easier to analyze.


Key preparation activities
- Reviewed the dataset structure.

- Standardized field naming.

- Checked numerical fields.

- Prepared date information for time-based analysis.

- Created/used Age Group classifications.

- Created a Year field from Invoice Date.

- Prepared revenue for aggregation.

- Used PivotTables for analysis.

- Used distinct counts where unique customers/transactions were required.

This preparation ensured that the dataset could support both descriptive analysis and business-oriented comparisons.


5. KPI Analysis


. Total Revenue - $251,505,794.25

This represents the total revenue generated across the dataset.

Observed Insight: The dataset represents a substantial retail sales volume, providing enough transaction activity to examine customer, product and location-level patterns.

Key Insight Derived: Revenue alone does not explain performance. The next question is where the revenue comes from and which customer/product/location characteristics are driving it.


. Total Orders - 99,457

The dataset contains 99,457 invoice transactions.

Key Insight Derived: Transaction volume provides context for the $251.51M revenue figure. Using the total revenue and transaction count:
Average Transaction Value  $251,505,794.25 ÷ 99,457 = approximately $2,528.91, This means the average transaction generated approximately $2,528.91 in revenue.

Actionable Recommendation: The business can use Average Transaction Value as a monitoring KPI and explore strategies such as: Product bundling, Cross-selling, Upselling. Complementary-product recommendations, Premium product promotion.


6. Customer Analysis

Unique Customers - 99,457

The analysis returned a distinct count of 99,457 Customer IDs. This metric should be clearly distinguished from simply counting customer records.

Analytical Thinking

A basic analysis might say:

"There are 99,457 customers."


A stronger analytical question is:

Are these customers making repeat purchases, or does the transaction count largely represent one transaction per customer?
Because the number of unique customers and invoice transactions are identical in this dataset, this deserves further investigation.


7. Revenue by Age Group


Age Group - Revenue

Middle Age -  $98.40M

Young - $86.00M

Old - $67.10M

Total -  $251.51M

Observed Insight: The Middle Age customer group generated the highest revenue at approximately $98.40M, The Young segment followed with approximately $86.00M, while the Old segment generated approximately $67.10M.

Key Insight Derived: The Middle Age segment is currently the strongest revenue-generating age group. However, the Young segment is also highly valuable and represents a significant portion of total revenue.

Actionable Recommendation

The business should:

- Protect and retain the Middle Age segment.

- Develop targeted campaigns for Young customers.

- Compare Average Transaction Value across age groups.

- Develop age-specific promotions rather than applying the same marketing strategy to every customer.


8. Product Category Analysis

The analysis intentionally measured Total Price by product category, This is different from revenue.


Total Price by Category

Category  -  Total Price

. Clothing - $31.08M

. Shoes  - $18.14M

. Technology - $15.77M

. Cosmetics  -  $1.85M

. Toys  -  $1.09M

. Food & Beverage  -  $231.57K

. Books  -  $226.98K

. Souvenir  -  $174.44K

Observed Insight: Clothing has the highest aggregate price value at approximately $31.08M, followed by Shoes and Technology.

Key Insight Derived: Clothing, Shoes and Technology represent the strongest categories based on the aggregate Price field. However, because this is Total Price rather than Revenue, it should not be interpreted as the category's actual revenue contribution. This distinction is important.


9. Average Unit Price by Category

Category  -  Average Unit Price

. Technology  -  $1,050.00

. Shoes  -  $600.17

. Clothing  -  $300.08

. Cosmetics  -  $40.66

. Toys  -  $35.84

. Books  -  $15.15

. Souvenir  -  $11.73

. Food & Beverage  -  $5.23

Key Insight Derived: Technology has by far the highest average unit price at $1,050, despite Clothing having the highest aggregate Total Price. This is a particularly interesting finding because it shows why one metric should not be used to judge category performance.

Analytical  Insight: Clothing wins on aggregate price value, while Technology wins on price per unit, That raises a deeper business question:


Is Clothing performing strongly because of higher purchase volume, while Technology generates value through higher-ticket purchases?


That should be investigated using Quantity and Revenue together.


10. Shopping Mall Performance

Shopping Mall  -  Revenue

. Mall of Istanbul  -  $50.8M

. Kanyon  -  $50.5M

. Metrocity  -  $37.3M

. Metropol AVM  -  $25.3M

. Istinye Park  -  $24.6M

. Zorlu Center  -  $12.9M

. Cevahir AVM  -  $12.6M

. Viaport Outlet  -  $12.5M

. Emaar Square Mall  - $12.4M

. Forum Istanbul  - $12.3M

Observed Insight: Mall of Istanbul generated the highest revenue at approximately $50.87M, narrowly ahead of Kanyon at approximately $50.55M.

Key Insight Derived: Revenue is concentrated among a small number of high-performing shopping malls. The difference between the top two malls is relatively small, suggesting that Mall of Istanbul and Kanyon are both strategically important locations.

Actionable Recommendation

Management should investigate what drives the performance of these malls:

- Product mix

- Customer demographics

- Transaction volume

- Average transaction value

- Store traffic

- Promotional activities

- Successful strategies from high-performing malls could potentially be adapted to lower-performing locations.


11. Most-Used Payment Method

The analysis measured payment method using Quantity.

Payment Method  -  Quantity

Cash  -  133,370

Credit Card  -  105,045

Debit Card  -  60,297

Observed Insight: Cash is the most-used payment method based on the quantity measure used in the analysis.

Key Insight Derived: Customers demonstrate a strong preference for cash transactions within this dataset.

Actionable Recommendation: The business should maintain efficient cash-payment processes while continuing to encourage digital payment options through:
- Card promotions

- Loyalty incentives

- Digital payment rewards

- Faster checkout options


12. Purchasing Pattern by Gender

The analysis indicates:

- Female purchasing share: approximately 59.81%

- Male purchasing share: approximately 40.19%

Observed Insight: Female customers account for a larger share of the purchasing quantity in the dataset.

Key Insight Derived: Female customers represent the stronger purchasing-volume segment. However, purchasing quantity does not necessarily mean higher revenue.


13. Sales Trend


Year  -  Revenue


2021  -  $114.56M


2022  -  $115.44M


2023  -  $21.51M



Analytical Finding — 2023 Is a Partial Year

The dataset's original Invoice Date runs from:

January 1, 2021 → March 8, 2023



Therefore:

2021 = full year

2022 = full year

2023 = only part of the year


The original annual revenue chart showed:

Year  -  Revenue

2021  -  $114.56M

2022  -  $115.44M

2023  -  $21.51M

A superficial conclusion would be:

"Revenue crashed in 2023."

❌ That conclusion is not valid.

Why?

Because you're comparing:

12 months vs 12 months vs approximately 2 months.


Analytical  Re-analysis

I compare the same period: January 1 – March 8
Year  -  Comparable Revenue

2021 -  $20.77M

2022  -  $20.49M

2023  -  $21.51M

2023 is: 4.99% higher than 2022 and 3.57% higher than 2021

Key Insight Derived: The apparent 2023 revenue decline is largely a data-period effect, not evidence of deteriorating business performance.

Actionable Recommendation: For management reporting, never compare a partial year with complete years without clearly flagging the difference.

Use:

- Year-to-date comparison

- Same-period comparison

- Monthly trend analysis

- Year-over-year comparable periods

- This is one of the strongest insights in the entire project.


14. Overall Key Findings


Your project can be summarized through these major findings:

Finding 1 — Strong overall revenue
The dataset generated $251.51M in revenue.

Finding 2 — Middle Age customers lead revenue
Middle Age customers generated $98.40M, making them the strongest age group.

Finding 3 — Mall of Istanbul leads location performance
Mall of Istanbul generated approximately $50.87M, narrowly ahead of Kanyon.

Finding 4 — Clothing dominates Total Price
Clothing recorded approximately $31.08M in aggregate Total Price.

Finding 5 — Technology commands the highest unit price
Technology had an average unit price of $1,050.

Finding 6 — Cash dominates payment quantity
Cash accounted for the largest quantity of purchases.

Finding 7 — Female customers have higher purchasing volume
Female customers represented approximately 59.81% of purchasing quantity.

Finding 8 — 2023 requires validation
Reported 2023 revenue is significantly lower, The apparent 2023 revenue decline is largely a data-period effect, not evidence of deteriorating business performance.


15. Strategic Recommendations

Based on the analysis, I recommend this five major business actions:

1. Strengthen high-value customer segments: Prioritize Middle Age customers while developing targeted strategies to increase engagement among Young customers.

2. Replicate successful mall strategies: Study Mall of Istanbul and Kanyon to understand the factors behind their strong revenue performance.

3. Optimize category strategy: Clothing, Shoes and Technology should receive close attention because of their strong aggregate price values and Technology should receive additional attention because of its $1,050 average unit price.

4. Increase Average Transaction Value: Use Bundling, Cross-selling, Upselling, Complementary products, Premium product recommendations to increase the approximately $2,528.91 average transaction value.

5. Investigate customer retention: Because unique customers and transactions are both 99,457, the business should investigate whether customers are primarily one-time purchasers. If confirmed, customer retention could represent a major opportunity.

