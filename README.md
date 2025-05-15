1. Project Overview:
This project aims to analyze Instagram influencer data to understand the key metrics impacting their influence and to build a predictive model for influence scores. With the growing significance of digital marketing, understanding influencer metrics can help brands make informed decisions when choosing collaborators, optimizing marketing strategies, and improving ROI.

2. Data Description
i) The analysis uses a comprehensive dataset containing the following key features:

ii) Followers: Total number of followers for each influencer.

iii) Influence Score: Overall influence measure based on engagement and reach.

iv) 60-Day Engagement Rate: Average engagement rate over the last 60 days.

v) Total Likes: Total number of likes received across all posts.

vi) Country: Geographical region of the influencer.

3. Steps in the Analysis

i) Data Acquisition: Collected and loaded the dataset.

ii) Data Preprocessing:

iii) Handled missing values 

iv) Converted human-readable numbers (e.g., "1.2M", "5K") into numeric format

4. Exploratory Data Analysis (EDA):

i) Analyzed follower distribution and engagement trends

ii) Identified top influencer regions

iii) Examined correlation between key metrics

5. Model Building:

Linear Regression: Initial baseline model

Random Forest Regressor: Tuned model for capturing complex interactions

6. Model Evaluation:

Evaluated models using RMSE and R² metrics for both train and test sets

i) Linear Regression:

Train RMSE: 5.86

Test RMSE: 13.26

Train R²: 0.37

Test R²: -0.04

ii) Random Forest Regressor:

Train RMSE: 2.69

Test RMSE: 12.77

Train R²: 0.87

Test R²: 0.04

7. Key Insights

i) Smaller accounts tend to have higher engagement rates, while larger accounts show a decline in direct audience interaction.

ii)The model struggles to generalize due to complex, non-linear patterns in the data, suggesting the need for more advanced feature engineering or alternative algorithms like XGBoost.

iii) The US dominates the influencer landscape, followed by Brazil and India, highlighting the importance of regional targeting.

Conclusion

This project provides valuable insights into the factors driving influence on Instagram and highlights the challenges in accurately predicting influence scores. With further optimization, this approach can significantly enhance influencer marketing strategies for brands.

Author

HANSA - Data Analyst Intern
