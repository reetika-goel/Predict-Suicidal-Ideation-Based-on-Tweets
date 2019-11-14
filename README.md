# CMPE-255-Miners

"Predict Suicidal Ideation Based on Tweets”

Identifying people with suicidal tendencies through social networks is a real social issue and an emerging research area with major challenges. The key challenge of suicide prevention is understanding and detecting the complex risk factors and warning signs that may precipitate in the event. This project presents an approach to understand suicidal ideation and cluster people with similar sentiment and location, with the goal of early detection via supervised and unsupervised learning.

The data is obtained using online user-generated content. This project demonstrates various classification and clustering techniques. Following are some of the traditional machine learning techniques implemented: Decision tree, Random forest, AdaBoost, etc. Deep Learning models also has been implemented such as LSTM and CNN models.

Dataset:

For Sentiment Classification (Positive - Negative)
	⁃	250,000 rows tweets
	⁃	Features: User ID, Date, Username, Date, Time,  Tweets, Sentiment

For Suicidal Ideation Classification(Suicide - Non Suicide Post)
	⁃	2000 rows Suicide twitter post
	⁃	Features: Tweets, Target Label

Clustering
	⁃	Features: Tweets, Latitude, Longitude, Sentiment, Suicide Label 

Models Used For Classification :

	•	DecisionTreeClassifier - Decision Trees are a type of Supervised Machine Learning where the data is continuously split according to a certain parameter. The tree can be explained by two entities, namely decision nodes and leaves.
  
	•	RandomForestClassifier - A random forest is a meta estimator that fits a number of decision tree classifiers on various subsamples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting.
  
	•	GaussianNB - It is the extension of Naive Bayes. To estimate the distribution of the data, Gaussian (or Normal distribution) is the easiest to work with because you only need to estimate the mean and the standard deviation from your training data.
  
	•	BernoulliNB - The Bernoulli naive Bayes classifier assumes that all our features are binary such that they take only two values.
  
	•	GradientBoostingClassifier - It is a machine learning technique for regression and classification problems, which produces a prediction model in the form of an ensemble of weak prediction models, typically decision trees.
  
	•	Extreme GradientBoostingClassifier - XGBoost is an algorithm that has recently been dominating applied machine learning and : competitions for structured or tabular data. It is an implementation of gradient boosted decision trees designed for speed and performance.
  
	•	Ensemble – GradientBoostingClassifier, RandomForestClassifier - Ensemble methods are meta-algorithms that combine several machine learning techniques into one predictive model in order to decrease variance (bagging), bias (boosting), or improve predictions (stacking).
  
	•	AdaBoostClassifier – DecisionTreeClassifier - AdaBoostClassifier can be used in conjunction with many other types of learning algorithms to improve performance.

Clustering Algorithms :

	•	K-Means - K-means clustering is a type of unsupervised learning, which is used when you have unlabeled data. The goal of this algorithm is to find groups in the data, with the number of groups represented by the variable K. The algorithm works iteratively to assign each data point to one of K groups based on the features that are provided. Data points are clustered based on feature similarity.
  
	•	DBSCAN - Density-based spatial clustering of applications with noise (DBSCAN) is a popular unsupervised learning method utilized in model building and is used in machine learning to separate clusters of high density from the clusters of low density. 
