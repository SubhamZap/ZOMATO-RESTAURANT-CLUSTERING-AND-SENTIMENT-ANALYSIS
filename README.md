# ZOMATO-RESTAURANT-CLUSTERING-AND-SENTIMENT-ANALYSIS

# Problem Statement: 
In today’s digitized modern world, the popularity of food apps is increasing due to their functionality to view, book, and order food with a few clicks on the phone for their favorite restaurant or cafes, by surveying the user ratings and reviews of the previously visited customers. 
The objective of the project is to analyze the dataset and make appropriate strategic decisions. The problem statement here asks us to cluster the restaurants to help customers find the best restaurants in their city and according to their taste and understand the fields they are lagging in. 
This will help Zomato in building a good recommendation system for their customers. Building a sentiment analysis model to understand the view of customer towards a restaurant and to identify the industry critics and especially work on their reviews to build a reputation worth praising.

# Data Structure: 
We are provided with two datasets for Zomato restaurant clustering and sentiment analysis project. The first dataset was meta_df which contains names, cost and cuisine columns. The second dataset was review_df which contains restaurants, reviewers, reviews, pictures, followers, time etc. Few null values from both the datasets were removed.

# Data Analysis: 
With various visualization techniques, we got to understand the relationship of different features. We found out expensive restaurants, high and low rated restaurants, cost of low rated restaurants, cuisines, critics with most followers. Clustering of dataset is done using Kmeans clustering. Dataset is clustered into five clusters according to cost, ratings and cuisines. Sentiment analysis was done to classify the words and phrases to predict the mood of the customers and to work on the reviews. For model prediction, sentiment is used as dependent variable
Various models like Logistic Regression, Random Forest, KNN and SVM were used to fit the data. Classification report of train and test set gave insight into the model performance. Confusion matrix showed the false positive and false negative part. SVM showed the least number of false positive, which means this model wrongly predicted a negative review as positive.

# Conclusion:

•	The best restaurants are AB's - Absolute Barbecues, B-Dubs, and 3B's - Buddies, Bar & Barbecue

•	The most popular cuisines are North Indian, Chinese, Continental, and Biryani.

•	The cheapest food joint is Mohammedia Shawarma and Amul and the costliest restaurant is Collage - Hyatt Hyderabad Gachibowli.

•	Rating decreased from year 2016 to 2018 but there is increase in rating from the year 2018 to 2019.

•	Amul has higher ratings with very low cost. It can be model restaurant for the restaurants with poor ratings.

•	Aarti Kamath and Supriya Subudhi are few reviewers with huge followings and gives mostly positive ratings. Sumit and D.S are few critics with huge followings.

•	SVM perform better than all other models, as it has the least false positive.
