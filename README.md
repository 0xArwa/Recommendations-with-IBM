# Recommendations-with-IBM

## Table of Contents
- <a href="#1"> Description </a>
- <a href="#2"> Installation </a>
- <a href="#3"> Project structure</a>
- <a href="#4"> Acknowledgements </a>

<a id='1'></a>
## Description

Recommendation systems have become an increasingly important tool in a variety of industries,
from e-commerce to entertainment. By analyzing user behavior and preferences,
these systems can provide personalized recommendations that improve user satisfaction and increase engagement. 
In this notebook, I will be building and exploring diffrent kinds of recommendation systems using an IBM dataset. 
The dataset contains user interactions with various articles that are a part of the IBM Watson Studio Community, 
and I'll be using this data to put the knowledge I learned from Udacity's courses to work.

This project cover these techniques:
- Rank-Based Recommendations
- User-User Based Collaborative Filtering
- Matrix Factorization using SVD
<a id='2'></a>
## Installation 
You can run this project on your local machine or using Google Colab. An HTML file is attached to view the code in a more convenient way.

<a id='3'></a>
## Project structure 

The files are organized in the follwoing structure: 

    data
      |- articles_community.csv
      |- user-item-interactions.csv
    |- Recommendations_with_IBM.html # html version
    |- Recommendations_with_IBM.ipynb # main notebook
    |- project_tests.py 
    |- top_10.p 
    |- top_20.p 
    |- top_5.p
    |- user_item_matrix.p 
    README.md
    
<a id='4'></a>
## Acknowledgements

The dataset belongs to IBM and this project is part of Udacity's Data Scientist Nanodegree. 
