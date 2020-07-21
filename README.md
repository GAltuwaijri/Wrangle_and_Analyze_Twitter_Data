# Wrangle_and_Analyze_Twitter_Data
We wrangle, Analyze and visualize WeRateDogs account data from twitter by using python and its libraries


## Table of Contents
- [Introduction](#intro)
- [Part I - Data Wrangling](#Wrangling)
   - [Gathering Data](#Wrangling)
   - [Assessing Data](#Assessing)
   - [Cleaning Data](#Cleaning)
- [Part II - Data Analysis and Visualization](#Analysis)


## Gathering data
We use the following three pieces of data in a Jupyter Notebook titled wrangle_act.ipynb:

- The WeRateDogs Twitter archive.
File downloaded manually. Link : data/twitter_archive_enhanced.csv.
- The tweet image predictions.
This file (image_predictions.tsv) is hosted on Udacity's servers and had been downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv
- Using the tweet IDs in the WeRateDogs Twitter archive, extract the file from the zipfile and read it in DataFrame.

## Assessing Data

***Visual assessment***
    - We displayed our three datasets df , df2 and df3 for visual assessment 
    
***Programmatic assessment***
    - programmatic assessment done by pandas' functions and other methods are used to assess the data.
    
## Cleaning Data

*After Assessing our datasets we found 5 Tidiness Issues and 10 quality Issues and cleaned them all*


## Storing Data & Reports
- cleaned data is stored in 'data/twitter_archive_master.csv'
