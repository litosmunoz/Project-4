# Project IV Sentiment Analysis API
## API - SQL query for Elon Musk's Tweets

<img width="90%" src="images/elon musk.webp" height="400">

### Project Goals
Main goal: Create an API that:

Serves information to clients (in response to their GET requests).
Receives data from your clients (via their POST requests) and saves it to your own database.
Remember, YOU (your API) are the server, and clients send GET or POST requests to you.

- Design the structure of your own database depending on the type of info you want to store.
- Write an API using flask to receive chat messages and store them in a database (mysql).
- Read and serve data from the chats database using different endpoints.

## 1 - Main Endpoint page for the API query:
    http://localhost:5000/


## 2 - Endpoint route to get all the tweets:

    http://localhost:5000/all


## 3 - Endpoint route to get total number of tweets: 

    http://localhost:5000/total/tweets


## 4 - Endpoint route to get the average number of Likes and Retweets per tweet:

    http://localhost:5000/average


## 5 - Endpoint route to get summary stats from the tweets (3 dictionaries):
    1. Number of Tweets per month
    2. Total Likes per month
    3. Total Retweets per month

    http://localhost:5000/summary


## 6 - Endpoint route to get Tweets from a specific month (in this case January):

    http://localhost:5000/tweets/1


## 7 - Endpoint route to get polarity score for one random tweet:

    http://localhost:5000/sentiment/random    


## 8 - Endpoint route to get polarity score for the top 10 most liked tweets: 

    http://localhost:5000/sentiment/likes/top10    


## 9 - Endpoint route to get polarity score for the top 20 most retweeted tweets: 

    http://localhost:5000/sentiment/rt/top20    
    

## 10 - Endpoint route for posting a new tweet:
 
    http://localhost:5000/post    



### Author:
Carlos Muñoz Fresco

### Documentation: 
The dataset was found on Kaggle. 
https://www.kaggle.com/datasets/marta99/elon-musks-tweets-dataset-2022