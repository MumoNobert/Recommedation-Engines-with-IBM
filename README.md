# Recommendation Engines 
This is a project on implementing recommendation engines for articles that users have interacted with on the IBM Watson Studio platform. The recommendation engines covered in this project are Rank Based Recommendation, User-User Collaborative filtering and Singular Value Decomposition(SVD) method.

## Table of Contents
1. [Project Motivation](#motivation)
2. [Installations](#installations)
3. [File Overview](#overview)
4. [Acknowledgements](#acknowledgements)

## <a id="motivation"/> Project Motivation
The motivation of this project was to bulid recommendation engines that can recommend relevant articles for a user interacting with the IBM Watson Studio platform. In particular I was looking to learn how to use user-item interactions to recommend users with content. Recommendations engines play
a big part in increasing user interactions on a platform as well as improving the user experience on the plaform.

## <a id="installations"/> Installations
This project mainly utilized Jupyter Notebook using Python; In addition the following libraties were used :
- pandas
- numpy
- mathplotlib
- seaborn

##  <a id="overview"/> File Overview
Files and folders included in this project include:
- data: This folder contains:
    - articles_community.csv file: contains data about articles available on the IBM Watson Studio platform
    - user-item-interactions.csv file: contains data that shows which user interacted with which articles
- Recommendations_with_IBM.ipynb : a jupyter notebook that contains all the work in building the recommedation engines
- Recommendations_with_IBM.html: a html file containing the contents of the jupyter notebook
- utilities: This folder contains
    - project_test.py : a test file containing tests used to validate functions in the projects
    - user_item_matrix.p: a piclke file that store a user-item interactions matrix created in the project
    - top.5.p/top_10.p/top_20.p: pickle files used in test to evaluate function in the prject


## <a id="acknowledgements"/> Licenses and acknowledgements
This project was worked on as part of the Recoomendation Engines module of the Udacity Data Scientist Nanodegree. The datasets are from IBM who have collaborated with Udacity to provide data to be used to complete this project. Code templates were also provided by [Udacity](https://www.udacity.com/) .