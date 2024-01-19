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
