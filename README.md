<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.udacity.com/course/data-scientist-nanodegree--nd025'>Udacity Data Scientist Nanodegree Program</a></h3>
<h1 align="center"> Recommendation Engines with IBM </h1>

The project files can be found [here](https://github.com/AliRezghi90/Recommendations-with-IBM.git) 

## Table of Contents
- [Introduction](#introduction)
- [Installation - Packages](#installation)
- [Summary - Methodology](#summary)
- [Licensing, Authors, and Acknowledgements](#licensing)
- 
## Introduction <a name="introduction"></a>
This project is a part of the Data Scientist Nanodegree by Udacity. In this project the interactions that users have with articles on the [IBM Watson Studio](https://www.ibm.com/products/watson-studio) platform are analyzed. knowledge-based filtering, collaborative filtering, and Singular Value Decomposition (SVD) methods are used tomake recommendations to IBM Watson Community users. 

## Installation - Packages <a name="installation"></a>
Use pip to install The following packages:
* Pandas
* Numpy
* Matplotlib
* pickle
* Jupyter

The program was appropriately run using Python 3.11., however, older versions might work as well.

## Summary - Methodology <a name="summary"></a>
The recommendation engine is created by implementing the following steps:
###### I. Exploratory Data Analysis
The data sets for articles cimmunity and user-item interactions are first explored to find some insights about the data. Next, the data sets are cleansed and prepared for recommendation models.

###### II. Rank Based Recommendations
Articels with most interactions are chosen as the most popular articles. The popular articles are especially used for new users as they do not present any interaction with the article community.

###### III. User-User Based Collaborative Filtering
To recommend article to users similar to other users, the user-user based collaborative filtering is an appropriate approach. A user-item matrix is created, which is used to find the users with highest similarities and the coreesponding articles. 

###### IV. Matrix Factorization
The Singular Value Decomposition (SVD) method is a well-known machine learning approach to build recommendation engines. Using the SVD, we will get an idea of how well we can predict new articles an individual might interact with. Since the user-item matrix does not have any NaN, there is no need to perform Funk SVD. 

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Credit must be given to [Udacity](https://www.udacity.com/) for the excellent Udacity Data Scientist Nanodegree program and also [IBM](https://www.ibm.com) for giving access to the pre-labeled data sets of their users and interactions. 

