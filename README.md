![image](https://github.com/KushalChakraborty1995/Play_Store_App_Review_Analysis/assets/114491920/80404769-d782-4c57-b092-91635089ceb1)

## Problem Statement:-                                                                                                                    
Data has been provided by ABC Advertising Pvt. Ltd. to analyze the data for different App in different categories and help them satisfy their customers needs who possibly resides around the world. From these analyses they can understand the needs of their customers in different aspects of product development and it will help solve the problems with the market superiors. The main objective of this project is to deal with the data provided by the company and to analyze the data in every aspect possible so to help them match their idea and help them to convert new and retain old customers and make reasonable growth. We have been provided with two datasets: Play Store Data.csv User Reviews.csv
## Play Store Data.csv column elements:-
App - Name of the Application
Category - Category of the Application
Rating - Rating given to the Application
Reviews - No of reviews given to the Application
Size - Size of the Application
Installs - No of downloads of the Application
Type - Free or Paid
Price - Price of the Application if it is paid
Content Rating-It is Age appropriate or Not
Genres - Type of Genre the Application belongs to 11.Last Updated - When the last time the Application is Updated
Current Ver - Current version of the Application
Android Version- Minimum Android version required to run the Application

## User Review.csv column elements:-
App:- Type of Applications
Translated_Review:- Reviews being given by consumer
Sentiment:- Sentiment of trust from customer
Sentiment_Polarity:- It determines sentimental expression of the customer's opinion
Sentiment_Subjectivity:- Sentimental Subjectivity in terms is a personal opinion and it falls in range [0,1].

## Problem Questions:-

Top Categories in Playstore?
Top Genres in the Playstore?
Top Content Rating per installation?
What is the percentage of free and paid Apps in the Play Store?
What is the effect of the last update on rating?
How does the last update have an effect on the trend of rating?
Effect on rating when the application was of type free and paid?
Relationship between reviews and rating?
relationship between Rating and Average Reviews
Average Rating of each App category
Average Rating for each genre

## Introduction:-

Android as we know is a huge marketplace where every app developer has the opportunity. When Google acquired Android in 2005. Google incorporated the market with android in 2007 which have let developers develop android applications and in this way with very less association with their own developer and more on open source developers it opened the markets of opportunities for both the makers and the user as well what we can easily speculate today. This has also helped in the development of many new businesses and also several new professions which we can experience now. There are basically three kinds of Applications in the Android Play Store. ‘Background Services and Intent Receivers Applications’,’Foreground Background Applications’ and ‘Intermittent Applications’.

The type of Applications which we will use to analyze in Play Store App Review Analysis mostly will be Intermittent type Applications.

In this project of Play Store App Review Analysis we will be analyzing each and every prospect of the data available with us and on the basis of this data we will try to solve every problem associated with the real world problem which lets them achieve customer prosperity.

## Data Cleaning and some insights:-

App - It tells us about the name of the application.
Category - It tells us about the category to which an application belongs.
Rating - It tells us about the ratings given by the users for a specific application.
Reviews - It tells us about the total number of users who have given a review for the application.
Size - It tells us about the size being occupied the application on the mobile phone.
Installs - It tells us about the total number of installs/downloads for an application.
Type - It tells us whether the application is free or a paid one.
Price - It tells us about the price of the application.
Content_Rating - It tells us about the target audience for the application.
Genres - It tells us about the various other categories to which an application can belong.
Last_Updated - It tells us about the when the application was updated.
Current_Ver - It tells us about the current version of the application.
Android_Ver - It tells us about the android version which can support the application on its platform.

## Conclusion and Insights:-

So here we come at the end of our project which is play store App Review Analysis.What we have done just take a short recap. First we have done the removal of null value from rows and columns and the same goes with the removal of duplicates from the datasets. Then we did the formatting for each of the required columns in each dataset. After analyzing the data we conclude that App with the category Family and the genre tools are in large numbers. Also we can conclude that the number App Rating is directly proportional with the recent update. From this we can see that with all the major updates apps will get more ratings. We can also conclude that most of the apps which are used by the users have a content rating of ‘Everyone’. In percentage of Free and Paid App Available in the PlayStore we can assume that most apps being used by the users are Free. This shows very few users purchase Apps on playstore. In rating vs count of App Type we conclude that rating is not get affected even if the app is paid or not but if we go on for finding the average rating we will find that free app will have less average rating compared to paid because of significantly high counts of free Apps as compared to Paid App available in App Store.

After moving forward when we performed analysis on sentiment subjectivity we found that most of the opinion on sentiment subjectivity lies high in the range 0.4 to 0.7. When we analyzed sentiment polarity for paid and free Apps we noticed that sentiment polarity for free apps is way less than paid Apps. In pie presenting the percentages of review sentiment we found that most of the sentiment are positive and neutral review is the lowest. Also in case finding the percentage of sentiments for top 5 Apps we found among top 5 App Category Health and Fitness has received the highest positive sentiments while Game app category has received the highest negative sentiments and Sports App Category has received the highest neutral sentiments. Important Points to be noted: After merging both of the dataset we find an Average Rating of 4.32. Also we can see that after merging both of the dataset the maximum Average Rating is 4.9. Also the average sentiment Polarity is 0.16 and average sentiment_subjectivity is 0.49 Also we have noticed that the average size of the Application available on playstore is 21933.38 KB. Lastly, all of the calculations and graphs in this project have accuracy in the range of 75% to 80%.

## Tableau Dashboard:-
![Dashboard 1](https://github.com/KushalChakraborty1995/Play_Store_App_Review_Analysis/assets/114491920/5212a5af-86cd-444c-aa37-efb52ebdbdb9)


![istockphoto-1132817705-612x612](https://github.com/KushalChakraborty1995/Play_Store_App_Review_Analysis/assets/114491920/eb85818b-938d-41a1-9aee-1313c98c4da5)

