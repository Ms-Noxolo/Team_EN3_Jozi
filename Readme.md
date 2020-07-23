# Recommender Systems
                    - Team EN3 Johannesburg


This repository hosts the scripts which will enable one to deploy a basic recommender engine based upon the Streamlit web application framework. The Jupyter Notebook in the repo shows a step by step walkthrough of how to build a recommender system based on the two mentioned approaches, and these steps have been rearranged in python scripts as well as the recommender systems in the recommender folder to facilitate serving the recommender in service. At a fundamental level, these systems operate using similarity, where we try to match people (users) to things (items).

### Overview
A recommender system is a information filtering system that seeks to predict the "rating" or "preference" a user would give to an item. Recommender systems are popular and utilized in a wide range of areas including books, movies, music, news and social media platforms. Recommender systems typically produce a list of recommendations in one of three ways – a simple recommender engine, collaborative filtering or through content-based filtering.

### Collaborative Filtering
This is an approach that builds a model from a user's past behaviour (items previously purchased or selected and/or numerical ratings given to those items) as well as similar decisions made by other users. This model is then used to predict items (or ratings for items) that the user may have an interest in

### Content-based Filtering
This is an approach that utilizes a series of discrete characteristics of an item in order to recommend additional items with similar properties.

#### Hybrid Recommender
This engine is one that combines the previous two previouly mentioned approaches.

Once can make different types of requests which will take them to different endpoints. In the directory of Recommender-movie, run the API locally: > python app.py. Using curl in the terminal for example, you can make a GET request at the URL of the API to get top n movies, similar to a particular movie via content, collaborative or hybrid filtering:

 
The accompanying repo https://github.com/Ms-Noxolo/unsupervised-predict-streamlit-template.git hosts the python scripts for the recommender built engines as well as instructions on how to run the recommeder system app hosted on streamlit both locally and on the cloud.