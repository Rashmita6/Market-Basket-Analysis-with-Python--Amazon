## Market-Basket-Analysis-with-Python--Amazon

# Project Overview
The project analyzes Amazon customer purchasing behavior using survey and transaction-level data to understand product affinities, customer segments, and recommendation effectiveness. Python was used to clean data, analyze behavior patterns, segment customers, and generate actionable business insights to improve cross-selling, personalization, and customer retention.

# Business Problem
● What products or categories are frequently purchased together, indicating cross-selling
opportunities?
● How do customer purchasing patterns vary across demographics or regions?
● Can we segment customers based on buying behavior to target personalized
promotions?
● Which products drive repeat purchases or high customer loyalty?

# Dataset summary
The dataset contains 800 records and 24 columns representing Amazon-style customer survey data including:
Customer demographics, Purchase categories, Browsing frequency, Cart abandonment reasons and Satisfaction ratings.

# Tools Used
● Python
● Jupyter Notebook
● Pandas
● NumPy
● Matplotlib / Seaborn
● Data Visualization 
● Scikit-learn (K-Means Clustering)

# Key Approach
# 1. Data Cleaning & Preparation
● Removed duplicate and inconsistent survey responses.
● Standardized categorical variables (gender, purchase frequency, recommendation responses).
● Handled missing values and corrected column naming issues.
● Converted rating and satisfaction fields to numeric format.

# 2. Descriptive Behavioral Analysis
● Analyzed customer demographics (age, gender).
● Identified most purchased product categories.
● Studied browsing behavior and cart abandonment reasons.
● Calculated average shopping satisfaction and review importance.

# 3. Customer Segmentation
Customers were segmented using behavioral metrics such as purchase frequency and satisfaction.
Segments Identified:
● Frequent Buyers: High frequency & high satisfaction.
● Occasional Shoppers: Moderate frequency & satisfaction.
● At-Risk Customers: Low satisfaction or frequent cart abandonment.
Techniques:
● Rule-based segmentation.
● K-Means clustering for behavioral grouping.

# 4. Market Basket & Recommendation Insights
● Analyzed product combinations frequently purchased together.
● Studied relationship between recommendation helpfulness and customer satisfaction.
● Evaluated impact of review reliability on purchase decisions.


# 5. Visualization & Reporting
● Bar charts for product categories and browsing methods.
● Heatmaps showing correlation between satisfaction and recommendations.
● Clear dashboards for management-level insights.

# Key Insights
● Customers who trust recommendations and reviews show significantly higher satisfaction.
● Frequent buyers prefer personalized suggestions, increasing repeat purchases.
● Cart abandonment is strongly linked to pricing issues and delivery concerns.
● Certain product categories are consistently bought together, indicating cross-sell opportunities.
● At-risk customers show low engagement with recommendations and reviews.

# Business Recommendations
● Use purchase history to suggest complementary products.
● Prioritize recommendations for frequent and loyal customers.
● Highlight verified and helpful reviews prominently.
● Encourage reviews through post-purchase nudges.
● Offer discounts or faster delivery options.
● Simplify checkout to reduce cart abandonment.
● Align inventory planning with high-affinity product pairs.
