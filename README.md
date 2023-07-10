# Twitter-Sentiment-Analysis-
The method of "computationally" assessing whether a piece of writing is positive, negative, is known as sentiment analysis. There are plenty of these works on the
microblogging site Twitter, which also incorporates events and emotions. With the help of several visualizations and analyzing techniques, this work aims to categorize customers’ perspectives expressed through tweets as either pleasant, neutral, or negative. The same thing can be represented visually using a word cloud.
 Additionally, we will organize the tweets into categories based on subjects like news, politics, sports, culture, and much more. Using the R programming language, the project will perform sentiment analysis to determine the opinion of the public on the conflict. The tweets dataset will be extracted through the Kaggle database. The analysis will be performed using NLP techniques and packages, such as text preprocessing, sentiment analysis, and visualization, to extract insights and draw conclusions, present in R studio. The results of this study will provide a deeper understanding of the attitudes and opinions of the public on this important global issue and its impact on international relations along with other regular affairs.

 This work also visualizes the data and concludes some important discussions present in the dataset.

## Dataset Link & Description: 
https://www.kaggle.com/datasets/kazanova/sentiment140

The Kaggle dataset contains a total of 1.6 million records with information related to tweets, including the target (polarity), ids, date, flag, user, and text. The dataset was collected in 2009 and is often used for sentiment analysis tasks.

Here is a brief description of each column in the dataset:

• target (0 or 4): The polarity of the tweet, where 0 denotes a negative tweet and 4 denotes a positive tweet.
• ids: The unique ID of the tweet.
• date: The date and time when the tweet was posted.
• flag: A query parameter used to filter tweets during data collection.
• user: The username of the Twitter user who posted the tweet.
• text: The text of the tweet.

## Flow-chart
![image](https://github.com/pulak2002/Twitter-Sentiment-Analysis-/assets/110912267/c0ebb69c-67ed-4e6c-bb01-9a8ac3f606f4)

## Applied ML &  Models

SVM (used Non-linear) :
The SVM Algorithm is frequently used for sentiment analysis, such as determining if a tweet has a positive, negative, or neutral attitude. The fundamental goal of SVM is to identify the best hyperplane in a high-dimensional feature space that discriminates between tweets with positive and negative sentiment.
The SVM algorithm can be used to categorise tweets according to their sentiment in the context of Twitter sentiment analysis. For instance, given a collection of tweets, SVM can be trained on a labelled subset of those tweets (i.e., tweets with known positive or negative sentiment) to develop a model that can precisely categorise fresh, unlabeled tweets as either positive or negative.The SVM algorithm's features can change depending on the particular sentiment analysis task at hand. For instance, features could include the presence or absence of particular words or phrases in a tweet, the frequency of a particular emoticon, or the use of a particular hashtag.SVM is an effective technique that may be applied to a variety of classification applications, such as sentiment analysis on Twitter. SVM allows us to find trends and patterns in tweets that can help us comprehend the general tone of a particular subject or event.

K NN Clustering:
The k-nearest neighbours algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier that uses proximity to classify or predict the grouping of a single data point. While it can be used for either regression or classification problems, it is most commonly used as a classification algorithm, assuming that similar points can be found near one another.It's also worth noting that the KNN algorithm belongs to a family of "lazy learning" models, which means it only stores a training dataset rather than going through a training stage. This also implies that when a classification or prediction is made, all computation occurs. Because it relies heavily on memory to store all of its training data.


