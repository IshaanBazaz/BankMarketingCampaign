The main reason for obtaining these analysis to target people who has a higher chance of becoming a potential customer based on their information obtained. This will help the marketing team to better target their potential clients

In this task we learned about data normalisation, one hot encoding to convert categorical data into numeric attributes and applying classification and clustering algorithms. 


## The Data attribute distribution.

We downloaded the data and uploaded it as a spark dataframe. Then we applied printSchema() on it and leaned that the data has 17 attributes. The label attribute was deposit and it was well balanced. However, the data was uncleaned and we had to clean it. Along with that we also dropped few of the unnecessary attributes, which can be derived from other attributes.


## The methods/algorithms you used for data wrangling and processing.

For data wrangling we used one hot encoding vector. This converts categorical data into numeric attributes and then using aggressor we combined them into a single feature. Then we normalized this feature attribute using Min Max Scaling technique. For applying further clustering and classification algorithm we used this scaled feature attribute.

## The performance of both unsupervised and supervised learning on the data.

For unsupervised learning of data we used clustering, and in that we used K-Means algorithm with k = 2. To measure the performance of this algorithm we used silhouette measure. The value of this was 0.92, which indicates the cluster was well divided from each other.

For supervised learning of data, we used classification algorithms, namely Logistic Regression, Decision Tree and Naïve Bayes. For measuring their performance we used accuracy metric.

Accuracy of Logistic regression was 75%.
Accuracy of Decision Tree was 77%.
Accuracy of Naïve Bayes was 74%.

Hence, Decision Tree was best.

## The important features which affect the objective (‘yes’ in ‘deposit’).

The import features which affect the objective are 'age', 'job', 'marital', 'education', 'default', 'balance', 'housing', 'loan', 'campaign', 'pdays', 'previous', 'poutcome'.


