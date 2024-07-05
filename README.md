# Tweet-Sentimental-Analysis
![Sentiment-analysis-of-Twitter-Social](https://github.com/shreathedev/Tweet-Sentimental-Analysis/assets/174740751/3c2b50ac-ab39-4dd6-a0f4-a6bba91ec29b)


This is used to classify any tweet as positive or negative .

Trained using random forst classifier and hyperparameter tuning.

Preprocessing steps:

tweet = input("Enter any tweet: ")

tweet = text_process(tweet)

tweet = remove_stopwords(tweet)

tweet = remove_emoji(tweet)

tweet = lemmatize_words(tweet)

tweet = cleanData(tweet)

tweet_list = [tweet]

TrainedDataVectorised = tfidf.transform(tweet_list)
