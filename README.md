# Recommendations with IBM
For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like. In order to determine which articles to show to each user, you will be performing a study of the data available on the IBM Watson Studio platform. You can create your own account to become a part of their community, and get a better understanding of their data by creating an account on the platform [here](https://dataplatform.cloud.ibm.com/).

## Project Outline
The project will be divided into the following tasks:

**I. Exploratory Data Analysis**
    
Before making recommendations of any kind, you will need to explore the data you are working with for the project. 

**II. Rank Based Recommendations**

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

**III. User-User Based Collaborative Filtering:**

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step towards more personal recommendations for the users.

**IV. Content Based Recommendations**

Given the amount of content available for each article, using your NLP skills might come up with some extremely creative ways to develop a content based recommendation system. 

**V. Matrix Factorization:**

You will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. 

**VI. Extras & Concluding:**

Using your workbook, you could now save your recommendations for each user, develop a class to make new predictions and update your results, and make a flask app to deploy your results.

## Instructions
This project requires **Python 3.x** version. And in order to complete this project, you need to install the following libraries:

- [numpy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org)
- [matplotlib](https://matplotlib.org/)
- [pickle](https://docs.python.org/3/library/pickle.html)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html).

I recommend installing [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### File Description
The main work is in the [project notebook](Recommendations_with_IBM.ipynb), and the pickle files are for code testing. 

### Data
The data is from IBM platform in csv format, and they are:
- `articles_community.csv`: contains full description of the articles.
- `user-item-interactions.csv`: contains user-article interactions.

