# TSP
Solving The Travelling Salesman Problem in R

# Assuming that I am a salesman for Coca Cola in Nigeria, I am required to compute the optimal route to use to visit all towns in the selected country following the principles of TSP.

To answer this question, I’m going to be exploring one of the most famous optimisation problems in mathematics: the Traveling Salesman Problem.

The Traveling Salesman Problem (TSP) is a classic optimization problem in computer science and mathematics. 
The objective is to find the shortest possible route that a salesman can take to visit a set of cities and return to the starting city, while visiting each city exactly once.

# The Data
I have compiled data on 35 major towns in Nigeria, including their respective latitude and longitude coordinates. 
Our objective is to determine the most efficient route that allows us to visit all 35 locations and return to our starting point. In order to do so, we require a distance matrix that calculates the distance between each venue.
To achieve this, we will utilize the geosphere package, which offers pre-built functions for computing distances based on the latitude and longitude coordinates of each venue.

I opted for the ompr TSP implementation, which proved to be both efficient and reliable*.
However, to utilize the vectorized version of the algorithm, we must obtain the developmental version of ompr.

 Make sure to check out ompr on github and follow the creator of this package on twitter,  @dirk_sch.
