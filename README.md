The project's goal is to generate video game recommendations based on user input and my steam library. This endeavor will assist those who wish to explore and discover new games.

The recommendation model is constructed with "NearestNeighbors," an unsupervised machine learning technique that employs distance calculation to determine the similarity or dissimilarity of data points.

Calculate the distance between the input and every data point in a dataset.
Choose the data points with the shortest distance as the nearest neighbors.
The model was developed using the following features:

The genre of the video game.
Platform: Platform for playing video games.
Rating: ESRB ratings
Critic Score: An aggregate score determined by Metacritic team.
User Score: The aggregated score of Metacritic's subscribers.


Video Game Recommendation Project Report

Project Objectives
This project aims to generate video game recommendations based on user input and their Steam library. The endeavor is intended to assist those interested in exploring and discovering new games.

Utilized Model: Nearest Neighbors
The recommendation model is built using "Nearest Neighbors," an unsupervised machine learning technique that employs distance calculation to determine the similarity or dissimilarity of data points.

Distance calculation: Calculate the distance between the user's input and every data point in the dataset.
Selection of nearest neighbors: Choose the data points with the shortest distance as the nearest neighbors.

Features Utilized
Video game genre
Platform: Gaming platform
Rating: ESRB rating
Critic Score: An aggregate score determined by the Metacritic team
User Score: The aggregated score of Metacritic subscribers

Data Cleaning and Processing
Handling missing values: Missing values have been cleaned, resulting in a complete dataset.
Imputation process: If Critic Score and User Score are missing, they are imputed using the mean scores.
Data Visualization
Visualizations depicting the distribution of data for genre, platform, and rating.
Similarity Analysis
Similarity between games calculated using cosine similarity.
Nearest neighbors identified and presented to the user.

Steam Library Analysis
Analysis of games in the user's Steam library.
Visualization of game genres in the library.

Recommendation Function
The video game recommendation function finds similar games based on a user-specified game.
Recommendations are filtered based on the genre and platform of the input game.

Results and Recommendations
The project successfully provides personalized video game recommendations to the user.
The recommendation system works effectively through similarity analysis and consideration of user preferences.
