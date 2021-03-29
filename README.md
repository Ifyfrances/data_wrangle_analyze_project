# data_wrangle_analyze_project
This repo is created for Udacity Data Analyst project on Wrangle and Analyze Data .
Task was to wrangle @WeRateDogs Twitter data, analyse the data and create visualizations to give further insights. 
This project encompasses the three phases of Data Wrangling which includes Data Gathering, Assessing and Cleaning.  
Data was gathered both manually (provided by Udacity) and programmatically. 
Additional data for retweet counts and number of "Likes" was collected using Twitter API "Tweepy" 

DATA GATHERING
Data gathering for this project was carried out in three phases.
Phase1: Manual data download:
Weratedogs twitter archive data, which contains some tweets, dog ratings was provided by Udacity
and I downloaded this data from the resources section for the course and saved on my local storage
as a csv file(twitter_archive_enhanced.csv).
Phase2:
The second data needed for this project, the tweet image projection data. This data was
downloaded programmatically using a get request from the Udacity’s server and saved on my local
storage as a tsv file( image_predictions.tsv )
Phase3:
The data dataset required for this project was downloaded using twitters’ API Tweepy. Using the
Tweet_ID for each tweet contained in the archived data from Phase1. I downloaded each tweets
retweet count and favorite(“Like”) count
ASSESSING DATA
After gathering the data, the next step was to assess the gathered data. I did this programmatically,
and some of them manually. I used pandas functions to assess the tidiness and the quality of the
data.
CLEANING
After assesing the various datasets, the issues highlighted were then corrected to make the data
clean and ready for visualisation. I followed three steps to complete each cleaning phase.
 Define: Define the issue
 Code: The code to correct the issue define.
 Test: To ensure method applied was functional and error/issue corrected
Cleaned datasets were merged using Pandas merge and stored as a .csv called twitter_archive_master.
VISUALISATION AND DATA ANALYSIS
I used the cleaned data to create some visuals and analysis to give more insight to the data and if
possible provide an understanding of the rating system applied by @WeRateDogs before rating dogs
