# BookRecommenderSystem

The Project is based on Recommendation Systems on books . With the help of various techniques/methodologies I was able to successfully create a recommender system for the users based on their previous viewing habits and based on their ratings.



## Why Recommender Systems ?
1. We tend to like things that are similar to other things we like
2. We tend to like things that are liked by similar people
3. These patterns can be used to make predictions to offer new things
4. Recommendation systems involve predicting users preferences for unseen items such as books 
5. Recommendation systems have become very popular with the increasing availability of millions of products online
6. Recommending relevant products increases the sales 

## Common Filtering Techniques
![Untitled](https://user-images.githubusercontent.com/75678122/130986576-46f4e6cc-2947-4988-b7c9-9f2120ebb0d2.png)



I have used collaborative filtering method based on Pearson correlation coefficient for the Recommender System.

With the help of Apache Spark ML implementation Alternating least squares (ALS) for collaborative filtering, a very popular algorithm for making recommendations.
ALS recommender is a matrix factorization algorithm that uses Alternating Least Squares with Weighted-Lamda-Regularization (ALS-WR). It factors the user to item matrix A into the user-to-feature matrix U and the item-to-feature matrix M: It runs the ALS algorithm in a parallel fashion. The ALS algorithm should uncover the latent factors that explain the observed user to item ratings and tries to find optimal factor weights to minimize the least squares between predicted and actual ratings.


