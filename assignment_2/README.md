# CE888 Module - Project 2 - Assignment 2
## Project Title: Fine-Tuning DeBERTa and BERTweet on Three Heterogeneous Tweet Classification Tasks

This repository contains all the code files for assignment 2 of the Data Science and Decesion Making module.  

##

## Performance
After fine-tuning, BERTweet outperformed the TweetEval leaderboard in two tasks, sentiment analysis and emotion recognition; while DeBERTa outperformed its bigger version (RoBERTa) in all three tasks. The macro-averaged recall score is reported for the sentiment analysis task and the macro-averaged F1 score is reported for both, hate speech detection and emotion recognition tasks.

### BERTweet Scores

  * Emotion Recognition: 83.27 (outperforming TweetEval Leaderboard 79.3)
  * Sentiment Analysis: 73.55 (outperforming TweetEval Leaderboard 73.4)
  * Hate Speech Detection: 56.05 (matching TweetEval Leaderboard 56.4)



### DeBERTa Scores

  * Emotion Recognition: 82.09 (outperforming TweetEval's RoBERTa Leaderboard 76.1)
  * Sentiment Analysis: 72.03 (outperforming TweetEval's RoBERTa Leaderboard 71.3)
  * Hate Speech Detection: 51.24 (outperforming TweetEval's RoBERTa Leaderboard 46.6)

##

### Notebooks' Structure:
All notebooks have been organized in the same manner, as follows:

  * Loading Libraries and Dataset
  * Exploratory Data Analysis
  * Exploring the tokenization and attention mask process
  * Pre-Processing Steps
  * Fine-Tuning and Evaluating the Model
     * Macro-Averaged Recall Score
    * Saving the best model
    * Loading the saved model 

##

### Datasets 
Three different datasets have been used to train and evaluate DeBERTa and BERTweet models. The datasets were provided by TweetEval, a unified benchmark for evaluating tweets classification: 
  * Hate Speech Detection Dataset ([Link](https://github.com/cardiffnlp/tweeteval/tree/main/datasets/hate)).
  * Emotion Recognition Dataset ([Link](https://github.com/cardiffnlp/tweeteval/tree/main/datasets/emotion)).
  * Sentiment Analysis Dataset ([Link](https://github.com/cardiffnlp/tweeteval/tree/main/datasets/sentiment)).
