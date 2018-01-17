# metro

Objective: Given a text file showing the population of a city and integer N, the city's budget, find a subway plan that would best serve the community while staying under budget. 

Constraints: Stations cost 3 monies and tracks 1. Stations must be connected by tracks. Tracks must be connected and may branch.

Example:  
Input:  
10  
1 1 2 1 1 1 1 1  
1 2 3 2 1 1 1 1  
1 2 2 1 1 1 1 1  
1 1 1 1 1 2 3 1  
1 1 1 1 2 3 3 1  
1 1 1 1 1 2 2 1  

Output:  
. . . . . . . .  
. . . . . . . .  
. . o x x . . .  
. . . . x x . .  
. . . . . o . .  
. . . . . . . .  
