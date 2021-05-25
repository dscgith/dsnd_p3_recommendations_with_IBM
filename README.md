--- 
# Recommendations with IBM

As part of the Data Science Nanodegree from Udacity this project shows some basic recommendation system approaches based on data from IBM.

---

#### Content
+ [Libraries used](#libraries-used)  
+ [Motivation](#motivation)  
+ [Data](#data)  
+ [What has been done?](#what-has-been-done)  
+ [Possible future Improvements](#possible-future-improvements)  
+ [Acknowledgements](#acknowledgements) 

---

### Libraries used
+ Pandas
+ Numpy
+ Matplotlib
+ Pickle
+ IPython

Python Version 3.6.3 was used for this project

---

### Motivation
The goal for this project was to get an understanding of basic recommendation algorithms and learn about common issues like the cold-start-problem.

---

### Data
The data to analyze contains the interactions that users have made with articles on the IBM Watson Studio platform.

| filename | file description |
| :-- | :-- |
| user-item-interactions.csv | A list of interactions of all users (article_id, article_title and anonymized email as user identification |
| articles_community.csv | Description and content of the articles |

The following files were provided by Udacity:  
+ user_item_matrix.zip (Pickle file, zipped because of file size)
+ project_tests.py
+ top_10.p 
+ top_20.p
+ top_5.p

---

### What has been done?
+ Exploratory Data Analysis
+ Rank Based Recommendations
+ User-User Based Collaborative Filtering
+ Matrix Factorization with SVD
    
---

### Possible future Improvements
* Set up a content based recommendation algorithm, based on natural language processing of the given article contents
* Write a class and deploy the recommendation system as a command line tool
* Provide the recommendation system as a web application

---
### Acknowledgements
Starter Code and test files were provided by Udacity as part of the Data Science Nanodegree project, the data was provided by IBM.

---
