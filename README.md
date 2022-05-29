# <h1 align="center">Algorithms</h1> 
# Movie Recommendation System
# About the Project 
* **Algorithms** project built during Microsoft Engage 2022.
* This is a simple movie recommendation system which is based on Content-Based Recommendation System.
* Content-based filtering is one of the popular techniques of recommendation or recommender systems. 
* The content or attributes of the things one likes are referred to as "content." Here, the system uses the features in order to recommend things that one might like.

## Salient Features
* When the similar movies are to be searched based on the contents of the input movie, this web application provides a list of the recommended movies using **Machine Learning(ML)**.
* If the input movie name is misspelled or not present in the database, it gives an error and provides an option to revisit the home page.

## Algorithm Used
* **Cosine Similarity** (the dot product for normalized vectors) is the Machine Learning model used to build the Movie Recommendation System.
* The recommendation system use the similarity matrix to recommend the next most similar movie to the user.
* The list of movies is sorted in the descending order, with the most similar movie at the top.

# Languages used
* HTML
* Python

# Dependencies
All the required dependencies are listed in the **requirements.txt** file.

# Navigating through the website
## Home page
It is used to input movies to find similar movie recommendations.

<img src="/images/home.PNG" width=700>

## Button at top right
Opens **Connect with me** page.

<img src="/images/side1.PNG" width=700>

## Found Movie Recommendations
* Opens up the page showing similar movie recommendations along with movie name and release date.

<img src="/images/positive.PNG" width=700>

* There is a google form to provide feedback at bottom of the page.

<img src="/images/form.PNG" width=700>
 
## Error Page
* It shows error if the input movie name is misspelled or not present in the database.
* It shows names of similar movies related to the input movie.
* It has a button which gives an option to revisit the home page and re-enter movie name.

<img src="/images/negative.PNG" width=700>
