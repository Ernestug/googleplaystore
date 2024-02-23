# Analysis of Mobile Apps in Google Playstore

## This project gives an insight of over 9000 mobile apps in the Google Play Store, analyzing the data to show apps with top reviews, app categories, content rating, and other relevant metrics.

##  Data Gathering

The dataset used for this analysis was gathered from [Kaggle](https://www.kaggle.com/datasets/bhavikjikadara/google-play-store-applications/data). The usability of the dataset was 10, which is the highest score for any dataset on Kaggle. Also, the completeness, credibility, and compatibility of the dataset was 100%, hence, the choice of working with the dataset. The data was sourced as a CSV file and was cleaned in Excel - ensuring there are no duplicates, using appropriate data types, and deleting unwanted columns. After cleaning and transformation was completed, the data was loaded to Power BI for analysis and visualization.

## Aggregated Metrics

Cards were used to show some metrics such as total number of apps used for the analysis, the number of app categories considered, as well as the maximum, average, and mimimum price of paid apps repsectively.

![](https://github.com/Ernestug/googleplaystore/blob/main/Cards.jpg)

## Category, Type, and Content Rating

Visualizations were done to show the distribution of the mobile apps by type (paid or free), category, and the content rating of the apps. For the category visual, the top 10 categories of mobile apps were visualized by the number of mobile apps in these categories.

![](https://github.com/Ernestug/googleplaystore/blob/main/Categories%2C%20Type%2C%20Content%20Rating.jpg)

## Top 10 Apps by Reviews

The top 10 mobile apps by the number of reviews received were also visualized in this analysis. Popular mobile apps like Facebook, Instagram, and WhatsApp took top spots in this chart.

![](https://github.com/Ernestug/googleplaystore/blob/main/Number%20of%20reviews.jpg)

## Mobile Apps by Average User Rating

Insights on the user rating on the various mobile apps were also visualized to show how many mobile apps have ratings, ranging from 1 to 5. From the dataset, various values of ratings were recorded from 0 to 5. To properly analyze these ratings, the "SWITCH FUNCTION" was used in creating a new column using a DAX that grouped these rating values into 0-1, 1-2, 2-3, 3-4, and 4-5. From this, the count of mobile apps under these respective groups of user ratings were visualized as shown below:

![](https://github.com/Ernestug/googleplaystore/blob/main/Avg%20User%20Rating.jpg)

## Remarks

Insights I was able to generate from this analysis are outlined below:

- **Top App Categories:** The dashboard shows that there are more apps from the family, game, and tools categories than any other category. One app could belong to several categories, however, the analysis shows that 0ver 35% of the entire apps in these analysis belonged to this category.
- **Mobile Apps with Top Reviews:** From this analysis, I observed that the top reviews were received from mobile apps under Meta Inc, that is apps like Facebook, Instagram, WhatsApp, and Messenger. These mobile apps are the most commonly used mobile apps in the world today, hence the number of reviews received from them.
- **Average User Rating:** From the analysis, I observed that over 65% of the mobile apps got ratings from 4 to 5 stars. This may tend to show some degree of acceptance and satisfaction from users who use these apps. This is also justified by the percentage (about 18%) of mobile apps who got low or no ratings from 0 to 2 stars. Mobile apps with ratings of 3 to 4 stars were about 16%. 
