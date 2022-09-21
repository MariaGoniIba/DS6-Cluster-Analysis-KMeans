# Data Science (DS) project 6: Cluster Analysis using K-Means with the Iris dataset
The [Iris flower dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set) is one of the most popular ones for machine learning. The dataset consists of 50 samples from each of three species of Iris (setosa, virginica and versicolor). There are 4 features: sepal length, sepal width, petal length, and petal width.

# Credit
The dataset and proposal of the exercise is from the Udemy course [The Data Science Course 2022: Complete Data Science Bootcamp](https://www.udemy.com/course/the-data-science-course-complete-data-science-bootcamp/). I highly recommend this course for those learning Python and machine learning.

# Steps
* We start with 2 clusters and observe the results
* We standardize the data and observe the difference in the results
* We use the Elbow method to determine the optimal number of clusters
* We plot the results using different number of clusters following the Elbow plot
* We compare our solutions to the original Iris dataset

# Conclusions
The Elbow method is not perfect. In this example, we may have opted for 2 or even 4 clusters, when there are actually 3. 
K-Means is very useful when we know in advance the number of clusters. 
