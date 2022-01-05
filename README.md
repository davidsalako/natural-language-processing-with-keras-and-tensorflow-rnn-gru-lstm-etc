# Natural Language Processing - Twitter US Airline Sentiment Analysis. - By David Salako.


## Background and Context.


Twitter possesses 330 million monthly active users, which allows businesses to reach a broad population and connect with customers without intermediaries. On the other hand, there is so much information that it is difficult for brands to quickly detect negative social mentions that could harm their business.

Sentiment analysis/classification, which involves monitoring emotions in conversations on social media platforms, has become a key strategy in social media marketing.

Listening to how customers feel about the product/service on Twitter allows companies to understand their audience, keep on top of what is being said about their brand and their competitors, and discover new trends in the industry.


## Objective.


To implement the techniques learned as a part of the course with the following learning outcomes:

* Basic understanding of text pre-processing.
* What to do after text pre-processing
* Bag of words
* Tf-idf
* Build the classification model.
* Evaluate the Model


## Dataset.


A sentiment analysis job about the problems of each major U.S. airline. Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service").

The dataset has the following columns:

* tweet_id                                                           
* airline_sentiment                                               
* airline_sentiment_confidence                               
* negativereason                                                   
* negativereason_confidence
* airline                                    
* airline_sentiment_gold                                              
* name     
* negativereason_gold 
* retweet_count
* text
* tweet_coord
* tweet_created
* tweet_location 
* user_timezone

There are 14,640 rows and 15 columns. 

===================================================================================================================================

The 'glove.6B.100d.txt' text file can be downloded from the Stanford University website (https://nlp.stanford.edu/projects/glove/).
