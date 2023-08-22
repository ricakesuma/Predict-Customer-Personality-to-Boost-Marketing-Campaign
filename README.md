# Predict Customer Personality to Boost Marketing Campaign

### Introduction
Predict Customer Personality to boost up marketing campaign performance by using Machine Learning. In this Mini Project, the role is that of a Data Scientist at a company as the core Data Science Team. The responsibility is to process historical marketing campaign data to increase performance and target the right customers so that they can transact on the company's platform. Here, the learning involves how to process data, clean data, create a machine learning model, and draw conclusions and business insights that can be recommended regarding the ongoing marketing campaign.

### Data Overview

| Field                 | Description                                                                                          |
|-----------------------|------------------------------------------------------------------------------------------------------|
| ID                    | Unique identifier for the customer.                                                                  |
| Year_Birth            | The year the customer was born.                                                                      |
| Education             | Educational background of the customer (e.g., High School, Bachelor's Degree, etc.).                 |
| Marital_Status        | Marital status of the customer (e.g., Single, Married, etc.).                                        |
| Income                | Annual income of the customer.                                                                       |
| Kidhome               | Number of children in the customer's household.                                                       |
| Teenhome              | Number of teenagers in the customer's household.                                                      |
| Dt_Customer           | Date the customer joined the company or became a customer.                                           |
| Recency               | Number of days since the last purchase or interaction with the company.                               |
| MntCoke               | Amount spent on Coke products in the last 2 years.                                                    |
| MntFruits             | Amount spent on fruit products in the last 2 years.                                                   |
| MntMeatProducts       | Amount spent on meat products in the last 2 years.                                                    |
| MntFishProducts       | Amount spent on fish products in the last 2 years.                                                    |
| MntSweetProducts      | Amount spent on sweet products in the last 2 years.                                                   |
| MntGoldProds          | Amount spent on gold products in the last 2 years.                                                    |
| NumDealsPurchases     | Number of purchases made with a discount.                                                            |
| NumWebPurchases       | Number of purchases made through the company's website.                                               |
| NumCatalogPurchases   | Number of purchases made using a catalog.                                                            |
| NumStorePurchases     | Number of purchases made directly in stores.                                                         |
| NumWebVisitsMonth     | Number of visits to the company's website in the last month.                                          |
| AcceptedCmp3          | Whether the customer accepted the offer in campaign 3 (1 for yes, 0 for no).                          |
| AcceptedCmp4          | Whether the customer accepted the offer in campaign 4 (1 for yes, 0 for no).                          |
| AcceptedCmp5          | Whether the customer accepted the offer in campaign 5 (1 for yes, 0 for no).                          |
| AcceptedCmp1          | Whether the customer accepted the offer in campaign 1 (1 for yes, 0 for no).                          |
| AcceptedCmp2          | Whether the customer accepted the offer in campaign 2 (1 for yes, 0 for no).                          |
| Complain              | Whether the customer has filed any complaints (1 for yes, 0 for no).                                  |
| Z_CostContact         | Constant value for the cost of contacting the customer (this might be a placeholder or reference value). |
| Z_Revenue             | Constant value for the revenue from the customer (this might be a placeholder or reference value).    |
| Response              | Whether the customer accepted the offer in the last campaign (1 for yes, 0 for no).                   |

### Step-by-Step

#### Step 1: Understand the Business Context and Data
- **Business Context:** The goal is to predict customer personality to enhance marketing campaign performance using machine learning.
- **Data Overview:** The data contains various attributes related to customers, their transactions, and interactions with different marketing campaigns.

#### Step 2: Data Loading and Exploration
- Load the data from the provided file.
- Perform initial exploration to understand the data structure, statistics, and potential issues such as missing or duplicated values.

#### Step 3: Data Cleaning and Preprocessing
- Handle missing values and duplicates.
- Perform feature engineering, such as calculating conversion rates and grouping customers by age.
- Encode categorical variables and standardize numerical features.

#### Step 4: Model Development
- Select the appropriate machine learning algorithm(s) for clustering or classification.
- Determine the optimal number of clusters using methods like the elbow method.
- Train the selected model(s) on the preprocessed data.

#### Step 5: Model Evaluation
- Evaluate the model's performance using metrics like silhouette score.
- Interpret the clustering results to understand customer segments.

#### Step 6: Business Interpretation and Recommendations
- Analyze the clusters to identify key customer segments that are more likely to respond positively to marketing campaigns.
- Provide recommendations for targeting specific customer segments to improve campaign performance and increase revenue.

#### Step 7: Potential Marketing Retargeting
- Select clusters for marketing retargeting.
- Calculate the potential revenue impact of retargeting selected clusters.

#### Step 8: Visualization and Reporting
- Create visualizations to represent the findings.
- Prepare a comprehensive report with insights and recommendations for stakeholders.

### Interpretation

#### Conversion Rate Analysis Based on Income, Spending, and Age
- **Young Group:** Higher conversion rate, indicating that marketing campaigns are effective for this age group.
- **Adult Group:** Moderate conversion rate, suggesting a good fit with current campaigns.
- **Older Group:** Lowest conversion rate, possibly requiring different marketing strategies.


#### Marketing Retargeting Strategy
- **Targeting Cluster 2:** Based on the profile, Cluster 2 was selected for marketing retargeting.
- **Cluster 2 Profile:** High income, high spending, positive response to previous offers, and fewer children and teenagers.
- **Retargeting Strategy:** Offer premium products, personalize offers, and consider strong online marketing strategies.

#### Potential Revenue Impact
The potential revenue impact of retargeting Cluster 2 was estimated at IDR 30,400,000.

### Business Recommendations:
1. **Target High-Value Segments:** Focus marketing efforts on customer segments identified as more likely to respond positively to campaigns.
2. **Personalize Campaigns:** Utilize customer insights to design personalized marketing strategies tailored to different segments.
3. **Monitor Performance:** Continuously monitor the performance of targeted campaigns and adjust strategies as needed.
4. **Invest in Retargeting:** Consider retargeting strategies for selected clusters to maximize revenue potential.
