# News Articles Analysis

Predictive analysis on the dataset taken from https://www.kaggle.com/asad1m9a9h6mood/news-articles.
It has news articles from 2015 till 2018, related to business and sports.


Following are the models we use for comparison 
1) K Nearest Neighbors [(KNN)](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
2) Forward-Feed Neural Networks [(FNN)](https://scikit-learn.org/stable/modules/neural_networks_supervised.html)
3) Logistic Regression [(LR)](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
4) Multinomial Naive Bayes [(MNB)](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html)

I used the 80-20 train test split.

| Classifier            	    | Accuracy  |
|-----------------------------------|---------- |
| K-Nearest Neighbours  	    | 94.06%    |
| Multi-layer Perceptron Classifier | 98.88%    |
| Logistic Regression               | 98.70%    |
| Multinomial Naive Bayes           | **99.62%**|

