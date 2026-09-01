Late Delivery, Low Review?

An exploratory data analysis project investigating the factors behind customer review scores in Brazilian e-commerce, with a particular focus on delivery performance, order volume, and seller maturity.

The analysis uses the Brazilian E-Commerce Public Dataset by Olist to explore an important question:

Does a low customer review score always come from late delivery?

Our findings suggest that delivery speed alone does not fully explain customer satisfaction. Seller performance, fulfillment consistency, and the overall customer experience also play important roles.

🎯 Problem Identification

Late delivery is commonly considered one of the main reasons customers give low review scores.

However, an interesting question arises:

If an order is delivered on time or even earlier than estimated, why can customers still give a low review score?

This project investigates whether factors beyond delivery delays can help explain variations in customer satisfaction.

🔍 Analysis Approach

The analysis consists of three main stages:

1. Data Integration

Multiple datasets from the Olist e-commerce ecosystem were integrated into a single analytical dataframe, including:

Orders
Customers
Order Items
Products
Payments
Reviews
Sellers
Geolocation
2. Data Cleansing

The dataset was prepared for analysis through:

Missing value identification
Missing value imputation
Outlier detection using boxplots
Categorical missing-value handling
Data type conversion
Feature engineering
3. Exploratory Analysis

The analysis focuses on the relationship between:

Delivery delay and review score
Monthly order volume and review score
Seller transaction volume and review consistency
Delivery speed and customer satisfaction
Same-province vs. different-province delivery
💡 Key Findings
Insight #1 — Order Volume Does Not Consistently Reduce Customer Satisfaction

The first major increase in order volume occurred in November 2017, reaching more than 7,500 orders.

During this period, the average review score dropped to approximately 3.8. However, in the following months, the review score returned to a more stable level despite order volume remaining relatively high.

This suggests that a temporary increase in transaction volume does not necessarily lead to a persistent decline in customer satisfaction.

Higher order volume alone is not sufficient to explain lower review scores at the platform level.

Insight #2 — Seller Maturity Is Associated With More Consistent Reviews

When analyzing only orders delivered on time or earlier, sellers with higher transaction volumes tend to maintain more stable review performance.

Sellers with lower transaction volumes show a wider spread in review outcomes, suggesting greater inconsistency in customer experience.

This may indicate that sellers handling more transactions have developed more standardized fulfillment processes.

Seller maturity and operational consistency may play an important role in maintaining customer satisfaction.

Insight #3 — Faster Delivery Does Not Always Mean Higher Satisfaction

Delivery speed alone does not guarantee a higher review score.

For example, inter-province deliveries were completed up to 12 days earlier than estimated on average, yet their average review score was approximately 4.02, lower than the 4.20 average for deliveries within the same province.

This indicates that customer satisfaction is influenced by more than delivery speed.

Possible factors include:

Product condition
Seller service quality
Fulfillment experience
Overall customer experience

Earlier delivery ≠ automatically higher customer satisfaction.

📈 Main Takeaway

Customer satisfaction in e-commerce should not be evaluated solely through delivery speed.

Our analysis indicates that:

Delivery Performance + Seller Performance + Fulfillment Consistency → Customer Experience

A seller that consistently handles orders and maintains a standardized fulfillment process may provide a more predictable customer experience, even when individual delivery times vary.

Therefore, improving customer satisfaction requires a broader approach than simply reducing delivery delays.

🛠️ Tools & Technologies
Python
Pandas — Data manipulation and analysis
NumPy — Numerical operations
Matplotlib — Data visualization
Seaborn — Statistical visualization
Jupyter Notebook — Interactive analysis
