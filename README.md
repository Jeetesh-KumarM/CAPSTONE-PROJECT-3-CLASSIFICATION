# Coronavirus Tweet Sentiment Analysis on the COVID-19 pandemic

Project Summary:

We operated on Coronavirus Tweet Sentiment Analysis dataset for the year 2020 which includes several factors like Location, OriginalTweet, TweetAt, Sentiment and etc.The process followed:

1. Analysed the data- The number of rows and columns it had,type of the features presented,the kind of data each particular feature had,checked for duplicated or missing values.
2. Data manipulation- Checked for outliers and null values and fiixed it with the necessary operations.
3. Data Visualization - plotted various graphs and like Location,Monthly tweet,Type of Sentiment,Tweeted at, Word Cloud etc. charts to find out their affect on the Sentiment.Also plotted heatmap to find the correlation between different features.
4. Data Pre-processing and feature selection- Dropped the unnecessary columns and rows.Performed Text Data Processing like contraction,removing urls,punctuations and stopwords.Also performed tokenization and vectorization.
5. Model Implementation - 5 model have been created with different ML Algorithms:Logistic Regression,Decision Tree,Support Vector Machine,XG Boost and Random Forest.
6. To select the best model we considered Accuracy,Precision and Recall to evaluate the performance.
7. Accuracy will tell how many times the model was correct overall.
8. Precision will tell how good the model is at predicting a specific category.
9. Recall will tell how many times the model was able to detect a specific category.
10. Out of the 5 models Logistic Regression performed best so it was tuned to improve its score.So Tuned Logistic Regression turned out to be the best among the other models for our given dataset.

Conclusion:

Five Models have been tested -

1. Logistics Regression: Accuracy = 78.4464 %, Precision = 78.2148 % , Recall = 78.4464 %.
2. Decision Tree: Accuracy = 63.3558 %, Precision = 63.8142 % , Recall = 63.3558 %.
3. Support Vector Machine: Accuracy = 77.8170 %, Precision = 77.6483 % , Recall = 77.8170%.
4. XG-Boost: Accuracy = 63.1716 %, Precision = 63.7475 % , Recall = 63.1716%.
5. Random Forest: Accuracy = 74.2247 %, Precision = 74.2363 % , Recall = 74.2247%.
Since the score of Logistic Regression is the best, tuning the Logistic Regression increased the Accuracy to 78.4925 %, Precision to 78.3320 %, Recall to 78.4925 %
