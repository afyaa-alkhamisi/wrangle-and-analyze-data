# wrangle-and-analyze-data
## Project Overview

The goal of this project is wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. 
Furthermore, Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. 
These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc.
Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

We got WeRateDogs Twitter data from their twitter archive from November 2015 to August 2017.
We collected three sources of data for this project which are, the first is Enhanced Twitter Archive: contains very basic tweet information.
The second source is Additional Data via the Twitter API: we gathered each tweet's retweet count and favorite ("like") count.
The last source is Image Predictions File: is present every image in the WeRateDogs Twitter archive through a neural network.
Therefore, to create interesting and trustworthy analyses and visualizations, we've decided to ask the following questions:
- What is the most commonly used source for posting of tweets people? 
- Which are the most famous dog names? 
- How have the effects of retweets and favorites count changed over time? 
- Which are the most popular dog stages that people prefer? 
- Which stage of those popular dogs has the highest average rating? 
- What are the 10 most frequent predicted dog breeds?

**To achieve the main purpose of the project we followed the following steps:**
- Step 1: Gathering data
- Step 2: Assessing data
- Step 3: Cleaning data
- Step 4: Storing data
- Step 5: Analyzing, and visualizing data
- Step 6: Reporting
  - wrangle_report: our data wrangling efforts
  - act_report: our data analyses and visualizations

## Results
In the final analysis, based on WeRateDogs Twitter data, which we gathered from the datasets, then we assessed and cleaned them, this is the overall result:
- The most commonly  used source for posting of tweets people was "Twitter for iPhone" with 1955 counts.
- The most famous dog name were Charlie with 11 appearances of the name.
- The number of retweets and favorites has increased over time. Also, the number of likes was significantly more than the number of retweets.
- The most common dog breeds preferred by people were "pupper" and "doggo".
- The popular dog stage "doggo, puppo" has the highest average rating.
- The most frequent predicted dog breeds was golden_retriever with 158 predictios, 
followed by labrador_retriever with 108 predictios, and pembroke got 95 predictions. Then, chihuahua with 91 predictions, 
followed by pug with 62 predictions, toy_poodle with 51 predictions, chow with 48 predictions, pomeranian with 42 predictions,
samoyed with 42 predictions, and malamute with 33 predictions.

## File Description
```
- wrangle_act.ipynb : Jupyter Notebook file containing project code for gathering, assessing, cleaning, analyzing, 
and visualizing data
- wrangle_act.html : Another version in html file containing project code
- twitter-archive-enhanced.csv : File as given from the Udacity
- image-predictions.tsv : File downloaded programmatically
- tweet-json.txt : File constructed via API
- twitter_archive_master.csv : File combined and cleaned master dataset for the project
- wrangle_report.pdf : Documentation for data wrangling steps: gather, assess, and clean
- act_report.pdf : Documentation of analysis and insights into final data
- img folder : Image folder containing all images of the visualization data in the project
- README.md : This file, describing the contents of this repository
```

## Installation
We will install the following Python libraries for facilitate of analysis:
```
pandas
numPy
matplotlib
seaborn
requests
tweepy
json
```
It will be recommend to installing Anaconda, which comes with all of the necessary packages.

## Run
To run this project navigate to project directory in terminal and then use following command.
```
jupyter notebook wrangle_act.ipynb
```
## Licensing and Acknowledgements
This project was presented as part of the Data Analyst Nanodegree Program at Udacity.
