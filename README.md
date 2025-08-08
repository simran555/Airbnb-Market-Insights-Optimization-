<b> Airbnb Data Analysis and Predictive Modeling </b>

This project contains an in-depth analysis of an Airbnb dataset, exploring various aspects of listings, hosts, and guest behavior. The project aims to provide insights into market trends and build a predictive model for listing prices.

<b>Project Overview </b>
The project involved a comprehensive data analysis workflow, including:

. Data preprocessing and cleaning of a large-scale Airbnb dataset.

. Designing and implementing a star schema for data warehousing.

. Exploratory data analysis (EDA) to uncover key trends and patterns.
<img width="1794" height="811" alt="image" src="https://github.com/user-attachments/assets/4516ebc5-5744-4b66-b3c8-2d5805a024f1" />

. Developing predictive models to forecast listing performance.

. Deriving business implications and actionable insights.

<b> Dataset </b>
The analysis is based on an Airbnb dataset that was initially composed of 494,954 rows and 89 columns. This was transformed into a more manageable dataset with 1,476,500 rows and 34 columns. 

Key features of the dataset include:

1. Listing Details: Information about the properties themselves.

2. Host Details: Data on the hosts.

3. Location: Geographical information for each listing.

4. Property Information: Specifics about the property type and amenities.

5. Availability: Calendar data for booking availability.

6. Review Details: Guest review scores and comments.

<b> Methodology </b>
1. Data Warehousing
A star schema was designed to structure the data for efficient querying and analysis. The schema includes:

Fact Table: Listing_performance

Dimension Tables: dim_listings, dim_host, dim_location

2. Data Preparation & Exploration
The data was prepared through several steps:

Preprocessing: Dropping unnecessary columns and handling missing values by either imputation or removal. Outliers were detected and addressed to ensure data quality.

Transformation: Techniques such as scaling and one-hot encoding were applied. New features were engineered, including columns for calculating revenue, number of bookings, and host response time.

Exploratory Data Analysis (EDA): A variety of visualizations were created to understand the data, including:

. A bar graph showing that most hosts respond within an hour.
<img width="1153" height="858" alt="image" src="https://github.com/user-attachments/assets/93100690-0546-49f6-b413-8c138b502d8b" />


. A horizontal bar chart identifying timeshares as the most expensive property type and houses as the least expensive.
<img width="1243" height="732" alt="image" src="https://github.com/user-attachments/assets/f361177b-1e2e-4f01-bf64-d8ba7ac2fc66" />


. A histogram revealing that there are more affordable listings than expensive ones.
<img width="1052" height="651" alt="image" src="https://github.com/user-attachments/assets/015dbd11-dc1d-4d41-9343-b1083021fb93" />



. A donut chart indicating that apartments are the most common property type.
<img width="862" height="738" alt="image" src="https://github.com/user-attachments/assets/18fc7553-b9f2-43e0-a958-c80e14e3cc20" />


3.<b> Predictive Modeling </b>
Three different regression models were implemented and compared to predict listing performance:

. Linear Regression

. Decision Tree Regression

. Random Forest Regression

The performance of these models was evaluated to determine the most effective approach for forecasting.

<b> Key Findings & Business Implications </b>
The analysis yielded several key insights with practical business applications:

. Guest Satisfaction: Understanding the factors that contribute to positive reviews.

. Host Performance: Identifying characteristics of high-performing hosts.

. Listing Optimization: Providing recommendations for improving listing appeal and pricing.

<b> Potential applications for this project include </b>:

. Performance Analytics: Creating dashboards to monitor key metrics.

. Demand Forecasting: Predicting future booking trends.

. Property Popularity Metrics: Measuring the popularity of different listing types.

. Dynamic Pricing: Developing a system for real-time price adjustments.







