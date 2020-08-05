# Recommender-System
A content based movie recommendation system using movielens dataset

## Dataset Description :

   The data set is avalable on kaggle : https://www.kaggle.com/grouplens/movielens-20m-dataset
   
   Files movie.csv, rating.csv and tag.csv are utilized to build the system.
   
## Project Description :

   TfidfVectorizer is used for feature extraction followed by dimensionality reduction.
   
   Tfidf : Thses are the word frequency scores that highlight the more interesting words.
   
   ### TfidfVectorizer : It is used to transform the text into the feature vectors that can be used as input the estimator.
   
   To know more about Tfidfvectorizer : https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html
   
   ### Dimensionality Reduction :
   
   The number of input variables for a data set is referred as dimensionality.
   
   Large number of input features can cause poor performance of machine learning algorithms.
   
   So, dimensionality reduction techniques are applied to enchance the performs of algorithms.
