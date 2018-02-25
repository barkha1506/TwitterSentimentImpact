# Analyzing the impact of tweets on stock prices of companies
Authors: Barkha Thakur
Co-Authors:  Badarinath KS, Devansh Garg, Rachel Wolfe,Yuyang Zhang

This project was implemented as part of our Big Data course in MS in Business Analytics at University of Minnesota. 
It is divided into two parts as mentioned in the report under the descriptive analytics heading.

For carrying out the first part of the analysis i.e. Analysis of Tweets and the theme associated using Apache NiFi, Solr and Banana Dashboard, just following the steps in the report would provide the details necessary to implement it.

For the second part of the analysis i.e. Analyzing the impact of sentiment on stock price using Spark Streaming and Spark MLlib, the file 'TweetRead.ipynb' contains the python code for the twitter application and the 'Twitter' file contains the pyspark code to calculate sentiment analysis and linear regression. The files 'postive_words' and 'negative_words' contains the dictionary of positive and negative words required for calculating the sentiment. The detailed steps to carry out this part is mentioned in the report.

The handout of our project is also present in the repository by the name Handout.pdf
