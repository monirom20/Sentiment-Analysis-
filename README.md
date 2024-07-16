# Sentiment-Analysis-


This work presents a comprehensive study of knowledge distillation
applied to sentiment analysis using state-of-the-art transformer-based models like
BERT and its compact version, SmallBERT, as well as traditional neural network
architectures such as Convolutional Neural Networks (CNN) and Bidirectional Long
Short-Term Memory networks (LSTM). Knowledge distillation, a process where a
smaller model is trained to mimic the behavior of a larger, more complex model, has
emerged as a powerful technique for deploying high-performing neural networks in
resource-constrained environments.

In this study, we started by fine-tuning a BERT model for sentiment analysis on a
labeled dataset. Subsequently, the knowledge from this BERT model was distilled
into three different types of student models: SmallBERT, a CNN, and a BiLSTM.
Each of these student models offers various trade-offs in terms of model complexity,
computational requirements, and performance characteristics.

My task was to test how knowledge distillation works when doing sentiment analysis.
Sentiment analysis, also known as opinion mining, is a subfield of Natural Language
Processing (NLP) that aims to determine the sentiment expressed in a piece of text.
It involves determining whether the sentiment is positive, negative, or neutral, and is
often used to understand the attitudes, opinions, and emotions of a speaker or writer
with respect to some topic or the overall contextual polarity of a document.

I chose the COVID19 twitter dataset, which was downloaded from Kaggle. The
dataset is composed of tweets on the subject of coronavirus, which are classified
according to their sentiment. A description of the dataset:

UserName: A unique identifier assigned to each user that posted a tweet.
ScreenName: Another unique identifier assigned to each user.
- Location: The geographical location where the user that posted the tweet is
located. Some entries might be missing (NaN), which means the user didn’t
provide their location or it couldn’t be determined.
- TweetAt: The date when the tweet was posted.
- OriginalTweet: The actual text content of the tweet.
- Sentiment: This is the target variable, representing the sentiment of the tweet.
It is classified into different categories: "Neutral", "Positive", "Extremely
Negative", and "Extremely Positive"

# License
This project is licensed under the MIT License. 
