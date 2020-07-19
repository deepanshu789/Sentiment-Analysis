# Sentiment-Analysis

# Objective: -

    To find if a tweet a positive or negative.
    
# Dependencies:-

    1.NumPy
    2.Pandas
    3.Nltk
    4.Seaborn
    5.Matplotlib
    6.WordCloud
    7.Sklearn
    
# Detail: -
    I have taken the dataset from Kaggle. 

    URL - https://www.kaggle.com/arkhoshghalb/twitter-sentiment-analysis-hatred-speech?select=train.csv 
    This dataset comprises of 29530 rows and 3 columns. The dataset attributes are tweet_id, sentimen and tweet,where 
    tweet_id - a unique integer identifying the tweet, 
    sentiment is either 1 (positive) or 0 (negative),
    tweet is the tweet enclosed in ""
    
    I have cleaned the data. Such as punctuations, numbers and even special characters.
    Most of the smaller words do not add much value. I have removed those well.
    I have split every tweet into tokens.
    Understanding the common words used in the tweets using WordClould.
   
# Steps: -

    Data Handling

    1.Importing Data with Pandas
    2.Cleaning Data
    3.Exploring Data through Visualizations with WordClould and barplot.
    
    Data Analysis

    1.Supervised Machine learning Techniques
    2.LogisticRegression
    3.Plotting graphs
    
# Results: -

     I have used logistic regression and got a accuracy of 82.93%. 
