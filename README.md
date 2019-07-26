# Project: Recommendation System for IBM Watson Articles

![N|Solid](https://github.com/devindatt/IBM-Recommendation-System/blob/master/assets/watson_articles1.png)



## Introduction

To analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles we think they will like. Image is an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

Though the above dashboard is just showing the newest articles, you could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.

In order to determine which articles to show to each user, we can perform a study of the data available on the IBM Watson Studio platform. 

#### Sections in Notebook:

##### 1) Exploratory Data Analysis
Here I explored the data we are working with for the project. 

##### 2) Rank Based Recommendations
Here we found the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, we can make the assumption the articles with the most interactions are the most popular. These are then the articles we could use to make recommendations.

##### 3) User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, we looked at users that are similar in terms of the items they have interacted with. These items were then be recommended to the similar users. 

##### 4) Matrix Factorization

Finally, we used a machine learning approach to building recommendations. I used the user-item interactions to build out a matrix decomposition. I used this decomposition to make predictations on new articles an individual might interact with, which turned out not to be that great). 

#### Files & Folders Used:

| File | Description |
| ------ | ------ |
| data | Folder that holds all the precompiled user-item matrices (can take upto 30 mins to compute) |
| assets | Folder containing the images used in this project|
| .ipynb | The Juypter Notebook of all the Python code mentioned above |
| .html | The viewable version of the Juypter Notebook  |



