# SA-hashtag-politicaldomain
<b>Utilizing Hashtags for Sentiment Analysis of Tweets in The Political Domain</b>

The objective of this research is to investigate the benefit of utilizing hashtags to determine sentiment polarity of tweets in the political domain. We used the sentiment polarity of hashtags as the features in classification, proposed rules for automatically annotating dataset based on the number of positive and negative hashtags in the tweets, and proposed a method to enrich terms in the tweet by extracting hashtag terms. We named the number of positive and negative hashtags as SentiHT feature. The experiments and evaluation show that sentiment classification using SentiHT feature and the automatically labeled dataset using SentiHT has a very good accuracy of more than 95%. Moreover, SentiHT outperforms unigram feature when combined with Naïve Bayes, SVM or Logistic Regression algorithms, but the opposite occurs when using Random Forest algorithm. Based on computing time to build the model, we recommend using SentiHT feature combined with Naïve Bayes algorithm.

<b>Dataset</b><br>
This project used 3 dataset, Dataset A, B and C.
Please read the corresponding paper about the differences between these dataset.
The files of dataset A, B and C in this repositories is the dataset after preprocessing. We could not find the original one :(

These dataset is available for personal use, but if you want to publish paper using the dataset you should cite this publication:

<a href="https://www.researchgate.net/publication/312590328_Utilizing_Hashtags_for_Sentiment_Analysis_of_Tweets_in_The_Political_Domain">
Ika Alfina, Dinda Sigmawaty, Fitria Nurhidayati, and Ahmad Nizar Hidayanto, <i>Utilizing Hashtags for Sentiment Analysis of Tweets in The Political Domain</i>. In ICMLC (International Conference on Machine Learning and Computing) 2017, Singapore. DOI: 10.1145/3055635.3056631</a>
