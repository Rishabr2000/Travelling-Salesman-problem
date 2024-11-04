## Travelling-Thief-problem

Objective: 
The objective is to develop an Evolutionary Algorithm using Python, Numpy, lxml and datetime to 
solve the Travelling Salesman Problem (TSP). The aim is to find the best /shortest route to visit a 
specific set of cities and return to the city where started. This will be achieved by utilizing distance 
data in XML files for Brazil and Burma 
1.Data Extraction:  
1. Extract the distance matrix from the xml files, which represents the travel cost between 
cities 
2. Transform the square distance matrix into a matrix with zero diagonals 
2.Evolutionary Algorithm Implementation 
Initial Population: Generate a set of solutions (routes). 
Fitness Evaluation: Calculate the distance for each route in order to determine its fitness. 
Selection: Implement tournament selection twice in order to select two parent routes for breeding. 
The selection will be based on choosing the routes from chosen subsets. 
Crossover: Use single point crossover technique to create routes (children) by combining pairs of 
parent routes. 
Mutation: Introduce changes through swap mutation in order to maintain diversity among 
offspring. This will create two routes, which will then be evaluated for their fitness. 
Replacement: Replace the routes in the population with ones based on their fitness levels. 
3. Parameter Adjustment:  
Try out population sizes, tournament sizes and mutation rates to determine the optimal settings, 
for the algorithm. 
4. Evaluation of Performance: 
Once the termination condition is met, assess the effectiveness of the algorithm by analyzing the 
route obtained and its corresponding cost. 
5. Inspiration from Nature:  
Keep track of both the number of generations and fitness evaluations to observe how the 
algorithm progresses over time drawing inspiration from processes.
6. Accounting for Constraints:  
Make sure that each city is visited once in every route respecting the constraint of the Traveling Salesperson Problem (TSP). 
7.Experimentation:  
Execute the algorithm using extracted data for both countries and record the route along with its 
associated cost, for each country
