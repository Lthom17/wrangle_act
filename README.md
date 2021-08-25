# wrangle_act
Project focused on wrangling and assessing data

Introduction

The datasets that I am exploring are from the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a quirky, funny comment about the dog. These ratings have a denominator of 10 but the numerators are almost always greater than 10. The reason is because WeRateDogs loves dogs and rates most above 100%I. WeRateDogs has over 4 million followers and has received international media coverage.

I will be collecting my data from three different sources.

Sources

1.) twitter_archive_enhanced.csv - a file provided by Udacity

2.) img_predictions.tsv - a file hosted on Udacity's servers

3.) I will use the Tweepy library to query Twitter's API for additional data.  I will read this data into a json file and extract it from this file to create a dataframe.
