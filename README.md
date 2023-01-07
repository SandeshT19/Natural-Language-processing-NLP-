# Machine Learning Natural Language Processing

In this project I am going to Demonstrate and understand the Sentiment of different users about different USA airlines and how they react on twitter. This is best example airlines and can used to get feedback and issues from customers and understand their needs and issues.
As always, I am mostly focusing on coding and the data science technique to understand data and get most of it using NLP models as per my knowledge and understanding in this notebook. I have skip the theory part for the NLP and it functioning which you will get plenty of theoretical material on internet.
Following are the few articles which will help you to get basic understanding and theoretical concept about NLP and different technique.


# Reference materials 
- https://machinelearningmastery.com/natural-language-processing/
- https://towardsdatascience.com/your-guide-to-natural-language-processing-nlp-48ea2511f6e1
- https://www.analyticsvidhya.com/blog/2022/01/nlp-tutorials-part-i-from-basics-to-advance/#:~:text=What%20is%20NLP%3F,questions%2C%20text%20summarization%2C%20etc.

#Simple  best video
- https://www.youtube.com/watch?v=IiD3YZkkCmE


# Summary :
Provided dataset is the twitter data for the USA airlines.
This data has so much inforamtion about the users their feedback and imotions and customer experience they have in conversations on social media platforms.
This data become a key strategy in social media marketing ,feedback and customer experience for the airlines .
Listening to how customers feel about the product/service on Twitter allows companies to understand their audience, keep on top of what’s being said about their brand and their competitors, and discover new trends in the industry.
This data is scaped from feb-2015 for all US major airlines .

# Problem Stament :
As Datascientist we have to undertand simplyfy the data ,preprocess the data .
Find the insights from prepocess data towards Major airlines ,compair the data between them and orivide analysis on the data.
Do the sentiment analysis on the data to find the user experience as positive, negative, and neutral tweets,
Also categorizing negative reasons (such as "late flight" or "rude service" if any.
Find the insights from data that will help Airlines to make customers experience better and improve any service based on analysis which will help to grow the business .

# Dataset:
# The dataset has the following columns:

- tweet_id
- airline_sentiment
- airline_sentiment_confidence
- negativereason
- negativereason_confidence
- airline
- airline_sentiment_gold
- name
- negativereason_gold
- retweet_count
- text
- tweet_coord
- tweet_created
- tweet_location
- user_timezone


## What Steps we are performing  to achive  above objective:

1) Importing base packages.

2) Text preprocessing and Text cleaning.
- Remove html tags.
- Replace contractions in string.
- Remove numbers.
- Tokenization.
- Remove Stopwords.
- Lemmatized data.
- We have used the NLTK library to tokenize words, remove stopwords and lemmatize the remaining words.

3) Vectorization :
- Using CountVectorizer.
- Use TfidfVectorizer.
- Apply count vectorizer
- Tf-IDF vectorizer,

5) Hyper paramter tunning the model :

6) Predicting test scores with different matrices.

7) Printing the important features for the prediction as per best model.

8) Conclusion.

