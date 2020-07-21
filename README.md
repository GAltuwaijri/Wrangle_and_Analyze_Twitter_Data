# Wrangle and Analyze Twitter Data
We wrangle, Analyze and visualize WeRateDogs account data from twitter by using python and its libraries


## Table of Contents
- [Introduction](#intro)
- [Part I - Data Wrangling](#Wrangling)
   - [Gathering Data](#Wrangling)
   - [Assessing Data](#Assessing)
   - [Cleaning Data](#Cleaning)
- [Part II - Data Analysis and Visualization](#Analysis)



## Setup

In order to run the notebook, you'll need to install:

 the following packages (libraries) need to be installed. You can install these packages via conda or pip. Please revisit our Anaconda tutorial earlier in the Nanodegree program for package installation instructions.

    - Python 3.6
    - Jupyter (notebook or lab)
    - Pandas
    - Numpy
    - Matplotlib
    - requests
    - tweepy
    - json
    
 You need to be able to create written documents that contain images and you need to be able to export these documents as PDF files.


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




## Storing Data & Report

    cleaned data is stored in 'data/twitter_archive_master.csv'

Two reports:

    wrangling efforts are briefly described in wrangle_report.pdf.
    The three (3) or more insights the student found are communicated in act_report.pdf including visualization.
    
    
### Resources

[1]: Wikipedia, https://en.wikipedia.org/wiki/DoggoLingo

[2]: Udacity, https://review.udacity.com/#!/rubrics/1136/view

[3]: matplotlib, https://matplotlib.org/3.1.0/gallery/statistics/barchart_demo.html#sphx-glr-gallery-statistics-barchart-demo-py

