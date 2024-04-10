# Unlocking Customer Insights: an RFM-Based Segmentation Approach

## Objective
The objective was to segment the customer base of our online retail data.  I used the Recency, Frequency, and Monetary (RFM) model, offering insights into customer behaviors and spending patterns to enable targeted marketing strategies.

## Data
I utilized online retail data, focusing on transactions with identifiable customer IDs, a history of at least 6 months, and a minimum total spend over $100. We excluded transactions with zero quantity or negative unit prices.

## Methodology
- **RFM Metrics Creation:** Calculated days since the last purchase (Recency), number of purchases in the last 180 days (Frequency), and average spend in this period (Monetary).
- **Clustering Approach:** Applied K-means clustering to the scaled RFM data, identifying five distinct customer segments.
- **SWOT Analysis:** Each segment underwent a comprehensive SWOT analysis, revealing unique strengths, weaknesses, opportunities, and threats. This analysis informed targeted recommendations for each segment.

## Data Cleaning and Exploratory Analysis
- **Handling Missing Values and Inconsistencies:** Cleaned data for accurate analysis, focusing on complete customer records and realistic transaction data.
- **Data Type Corrections:** Ensured correct data formats for analysis.
- **Exploratory Data Analysis:** Conducted to understand variable distributions and customer behavior.

## Customer Profiles
1. **Occasional Shoppers:** Infrequent purchasers forming a significant part of the customer base.
2. **Lapsed Customers:** Previously regular customers now inactive, representing re-engagement potential.
3. **Consistent Customers:** Regular buyers contributing most to revenue.
4. **Big Spenders:** Customers making rare but high-value purchases.
5. **Engaged Bargain Shoppers:** Frequent shoppers focused on deals, engaging regularly but spending less.

## Recommendations
- **Occasional Shoppers:** Targeted marketing to increase purchase frequency.
- **Lapsed Customers:** Personalized outreach for re-engagement.
- **Consistent Customers:** Loyalty programs and exclusive offers.
- **Big Spenders:** Premium services and personalized experiences.
- **Engaged Bargain Shoppers:** Continuous value through deals and community engagement.

## Conclusion
This study demonstrates the effectiveness of RFM segmentation in understanding customer behavior, guiding targeted marketing efforts and strategic business decisions. The use of clustering and SWOT analysis offers a comprehensive view of the customer base, providing a foundation for focused customer engagement strategies.
