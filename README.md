# Recommendations_with_IBM

#Introduction:
.
In this project, we will work with the user-article interaction dataset from the IBM Watson Studio platform, which contains information about which users have interacted with which articles. This dataset includes information such as article titles, article descriptions, and the type of user interaction (e.g. whether the user viewed the article, shared it, or commented on it).

#Libraries used:
.
-pandas as pd
-numpy as np
-matplotlib.pyplot as plt
-pickle

.

#Project Motivation:
.
The objective of the project is to build a recommendation system that suggests new articles to users based on their previous interactions with articles on the platform.

.

#File Description:
.
-Recommendations_with_IBM.ipynb:contains the main code for the project

-project_tests.py:includes testing code to ensure the functions in the Recommendations_with_IBM.ipynb notebook are implemented correctly 

- Top_5.p , Top_10.p , Top_20.p

-User_item_matrix.p

#Summary:
.
The Recommendations with IBM project involves various methods for building article recommendation systems. The project starts with exploratory data analysis to understand the distribution of user interactions with articles. Next, rank-based recommendations are implemented based on the most popular articles. User-user collaborative filtering is then used to make personalized recommendations based on similarities between users. Content-based recommendations are explored using article content, and finally, matrix factorization techniques such as SVD are used to extract latent features from the user-item interaction matrix and make article recommendations based on these features. The project also includes testing code to ensure the functions are implemented correctly. Overall, the goal is to create a personalized and effective recommendation system that helps users discover new articles of interest.
