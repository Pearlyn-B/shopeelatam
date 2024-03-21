# Shopee LATAM Sales-Dashboard

Note: This project was completed as part of a capstone endeavor within a Data Analytics program I undertook. The datasets were provided by the educational institution and were altered (specific columns omitted or modified) to comply with privacy policies. As a result, the data may not accurately represent the true sales performance of Shopee LATAM.

## Problem Statement

This Power BI project aims to provide Shopee LATAM with a comprehensive analysis of their sales performance spanning the years 2019 to 2022 in four distinct markets: Brazil, Chile, Mexico, and Colombia. The dashboard is designed to offer insights into sales trends over the specified period, delve into customer demographics, highlight top-performing products/ product categories, and ultimately uncover potential opportunities for business growth, including product recommendation strategies.

## Tools Used
1. Power BI: Utilized for data cleaning and transformation processes, including DAX, calculated columns, groupings, and conditional columns, as well as for visualization purposes.
2. Python: Employed to develop a product recommender system, leveraging popularity and demographic data to tailor product suggestions.

 # Report Snapshot
 
![dashboard](https://github.com/Pearlyn-B/da-portfolio/assets/80374547/4b85e2a9-232d-4490-a026-b22bb65bf6d5)


## Findings

1. **Seizing Growth Opportunities in Sales Rebound:**
   - Analysis indicates a growth trajectory from 2019 to 2020, a minor dip in 2020-2021, and a subsequent rebound in 2021-2022. This rebound presents a tangible opportunity for strategic initiatives to sustain growth.

2. **Seasonal Patterns Impacting Sales Performance:**
   - Distinct dips in February and September suggest the need for proactive planning. Tailoring marketing strategies and promotions during these months can mitigate the impact and potentially boost overall sales.

3. **Dominance of Household Items Category:**
   - The Household Items category emerges as a standout sales performer, emphasizing its strategic importance in Shopee LATAM's market approach.

4. **Crucial Revenue Drivers: Middle-aged and Millennial Customer Segments:**
-  The demographic analysis underscores Middle-aged (40-54) (contributing to 32.64% of Total Gross Revenue) and Millennial (25-39) (contributing to 29.88% of Total Gross Revenue) shoppers as pivotal customer segments, collectively contributing to over 60% of the total revenue.

5. **Opportunities for Growth in Brazil:**
   - Despite ranking lowest in total revenue and average order size, Brazil presents an exciting opportunity for strategic interventions to foster substantial growth.

## Recommendations

1. **Enhancing Sales through Personalized Shopping Experiences:**
To boost sales and enhance the shopping experience, historical purchase data can be leveraged to provide customers with personalized recommendations. These recommendations are as follows:

   ### Popularity Based Recommendations:
![popularity_recco](https://github.com/Pearlyn-B/da-portfolio/assets/80374547/7deabc2f-2c7b-4e14-b8fd-30a366b142bc)

   -  This approach identifies the top 5 most purchased products across all customers, offering a straightforward method to highlight universally appealing items. This approach ensures that new users are presented with products that have a broad appeal, increasing the likelihood of purchase due to their proven popularity.
   
   ### Demographics Based Recommendations:
![demo_reco_1_updated](https://github.com/Pearlyn-B/da-portfolio/assets/80374547/4411d97e-fde8-4359-a584-9aeef70fd4f9)

   - For a more tailored experience, purchase patterns are segmented by demographic details such as gender, country, age group, and income. By grouping customers and identifying top purchases within these segments, Shopee can offer personalized product recommendations that resonate with the specific preferences and needs of each shopper.
      
![demographics_reco](https://github.com/Pearlyn-B/da-portfolio/assets/80374547/d71ff00d-83eb-44b8-8a20-5d67673e75f8)
   - A function has been developed to recommend products tailored to a shopper's individual demographics, significantly improving the relevance of the suggestions provided.

Example Use Case:
As seen above, the recommendation function is applied to suggest products tailored for a 28-year-old Brazilian shopper with an annual income of $60,000.

   ### Hybrid Model Implementation:
![hybrid_updatedx2](https://github.com/Pearlyn-B/da-portfolio/assets/80374547/44c50795-9daf-4e81-9e8b-8a0f3800eea8)

The hybrid recommendation model merges the broad appeal of popularity-based recommendations with the personalized touch of demographic-based recommendations. For a given individual, this model first selects the top products from the popularity-based list and then supplements them with personalized suggestions derived from demographic data.

2. **Seasonal Promotions:**
   - Introduce Seasonal Marketing Strategies in February and September to counteract historically low sales months. For example, Valentine's Day campaigns in February and Independence Day-themed promotions in Brazil, Mexico, and Chile in September.

3. **Retention of Key Customer Segments, Middle-aged and Millennials:**
   - Develop targeted loyalty initiatives for Middle-aged and Millennial customer segments, offering rewards and incentives aligned with their interests. Actively solicit their feedback to improve product selection and mobile application user experience to promote sustained engagement.

4. **Boosting Product Categorical Performance:**
   - Elevate the Household Items category's success by exploring exclusive collaborations. Partner with high-demand brands or artisans to introduce premium products, adding exclusivity and potential value to the category, thereby driving increased sales.
   - Consider expanding product variety in underperforming categories like active wear by onboarding more sellers.

5. **Optimizing Discount Structure for Sustainable Growth:**
 ![disc structure](https://github.com/Pearlyn-B/da-portfolio/assets/80374547/b8cb999f-7698-4665-9fdc-b5b4b4cff71f)
   - Examination of key factors influencing sales underscores the necessity for an optimized discount structure. Sustain consistent growth by maintaining maximum discounts below 21%, ensuring a well-balanced and sustainable increase in revenue.
