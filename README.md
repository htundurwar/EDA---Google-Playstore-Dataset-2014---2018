# EDA---Google-Playstore-Dataset-2014---2018
EDA on Google Play Store dataset (2014–2018) to analyze app categories, ratings, reviews, installs, and pricing. Includes data cleaning and visualization to uncover key trends and insights using Python.
# Introduction

With the rapid growth of smartphones and mobile applications, app marketplaces have become extremely competitive. The Google Play Store is one of the largest digital distribution platforms, hosting millions of Android applications across various categories such as Games, Education, Business, Health, and Entertainment. These apps differ widely in terms of popularity, user ratings, size, pricing, and installation counts.

This project performs EDA and Feature Engineering on the Google Play Store dataset to gain insights into app performance and user preferences. The analysis aims to identify the most popular app categories, the applications with the highest number of installs, largest app sizes, and other key factors that influence an app’s success. These insights can help developers, marketers, and business stakeholders make informed decisions regarding app development, optimization, and market strategy.

The data consists of 20 column and 10841 rows.
## Report Structure 
This report is organized as follows:

1.Data Overview – Provides an overview of the Google Play Store dataset, including the data source, number of records and features, description of key variables, and initial observations about the data.

2.Data Preprocessing – Covers data cleaning steps such as handling missing values, correcting data types, removing inconsistencies, and preparing the dataset for analysis and feature engineering.

3.Exploratory Data Analysis – Involves statistical analysis and visualizations to explore relationships between variables such as app category, ratings, installs, reviews, size, and pricing. This section highlights key patterns, trends, and insights derived from the data.

4.Conclusion – Summarizes the main findings and insights obtained from the exploratory data analysis and feature engineering process.

5.Recommendations – Provides actionable recommendations for app developers and businesses based on the analysis results, such as category selection, pricing strategy, and app optimization.
## Business Questions Based on Available Columns 
1. Category & Popularity
    * Which app category has the highest number of apps on the Google Play Store?
    * Which categories receive the maximum total installs?
    * Which genres are most popular within each category?
2. User Engagement & Ratings
    * What is the average rating per category?
    * Do apps with higher ratings receive more installs?
    * Does the number of reviews influence an app’s rating?
    * Which categories have the most user engagement based on review count?
3. App Size & Performance
    * Is there a relationship between app size and user ratings?
    * Do smaller-sized apps get more installs compared to larger apps?
    * Which categories tend to have larger app sizes?
4. Free vs Paid Apps
      * Are free apps downloaded more than paid apps?
    * What is the average rating of free apps vs paid apps?
     * Which categories contain the highest number of paid apps?
    * How does app price affect installs for paid apps?
5. Content Rating & Audience
     * Which content rating (Everyone, Teen, Mature, etc.) is most common?
      * Do apps with ‘Everyone’ content rating receive more installs?
     * How does content rating vary across categories?
6. Market & Business Insights
    * Which categories show high demand but low competition (good for new app development)?
    *  What combination of price, size, and rating leads to higher installs?
    * Which app features are most important for business success on the Play Store?
