#Intelligent Recommendor System Based on Textual Content:

**Objective**:
Provide a great user experience for students on Xloosv app (private social communication platform) by predicting most interesting posts!

**Focus**: choose the best feature engineering techniques or implement a new one that could improve the accuracy. 

**plan**:
1.  Predict the best posts (Part 1):

  - predict the number of upvotes a post will receive based on its textual content (NLP) and store it in a "NLP score" variable
  - use Elasticsearch Decay Function to predict the best 10 posts to show based on:

      1. creation Date
      2. number of likes
      3. number of comments
      4. NLP score

2. predict the hashtag/topic/subreddit of a post based on its textual content (Part 2)

Other possible tasks:

  * Merge the models to the Xloosv app using Firebase ML then make it continue learning and improving from future data
  * repeat the previous tasks, but based on image content (for posts that contain images)

**Dataset**:  

A large collection of Reddit posts:
- https://github.com/umbrae/reddit-top-2.5-million/
- https://www.kaggle.com/unanimad/dataisbeautiful
