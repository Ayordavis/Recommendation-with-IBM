# Recommendation-with-IBM
Recommendation with IBM
Recommendations with IBM Project (Udacity - Data Scientist Nanodegree Program)
Table of Contents
Introduction
File Descriptions
Installation
Instructions
Acknowledgements
Introduction
This project is part of the Udacity's Data Scientist Nanodegree Program in collaboration with IBM.

In this project, we will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles we think they will like.

Our Tasks
The project is divided into the following tasks:

i. Exploratory Data Analysis
Before making recommendations of any kind, we will need to explore the data we are working with for the project. Dive in to see what we can find. There are some basic, required questions to be answered about the data we are working with throughout the rest of the notebook. This space is used to explore, before we dive into the details of our recommendation system in the later sections.

ii. Rank Based Recommendations
To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

iii. User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. We will implement this next.

iV. Content Based Recommendations (EXTRA - not required for completing this project)
Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using our NLP skills, we might come up with some extremely creative ways to develop a content based recommendation system. We are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

v. Matrix Factorization
Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using our decomposition, we will get an idea of how well we can predict new articles an individual might interact with (spoiler alert - it isn't great). we will finally discuss which methods we might use moving forward, and how we might test how well our recommendations are working for engaging users.

File Descriptions
Recommendations_with_IBM.ipynb - Jupyter Notebook for project
project_test.py - Python file contains solutions for test questions in the Jupyter Notebook.

top_10.p - P file contains top 10 articles.
top_20.p - P file contains top 20 articles.
top_5.p - P file contains top 5 articles.
user_item_matrix.zip - zipped file for user_item_matrix.p. We need to unzip the file to use it. This is P file containing user item matrix that we will use to perform Singular Value Decomposition (SVD).
(Note: P files are used by project_test.py to test top n articles we obtained via functions we created.)

Folder: data
articles_community.csv - articles available on the IBM platform
user-item-interactions.csv - list of articles that users interact with

Installation
There should be no extra libraries required to install apart from those coming together with Anaconda distribution. There should be no issue to run the codes using Python 3.5 and above.

Libraries Used
pandas, numpy, matplotlib, pickle

Instructions
Run the codes inside Jupyter notebook to complete the project.

Future Work
Using the notebook, we could now save our recommendations for each user, develop a class to make new predictions and update our results, and make a flask app to deploy our results.

Acknowledgements
Udacity for providing an excellent Data Scientist training program.
IBM for providing user interaction article dataset from IBM Watson Studio.
