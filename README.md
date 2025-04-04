# Max_Min_Ant_Colony_Optimization
## Members:
- Đinh Tuệ Đức
- Đào Minh Hải
- Nguyễn Văn Giáp
## Introduction:
Our group implement the MMACO (Max-Min Ant Colony Optimization) algorithm, a metaheuristic approach inspired by the behavior of ant colonies in nature. MMACO enhances the basic ACO (Ant Colony Optimization) algorithm by incorporating a pheromone value limitation mechanism (max-min), which prevents premature convergence to suboptimal solutions and improves exploration of the solution space. This project offers an efficient method for finding optimal routes in the ThOP (Traveling Highwayman Orienteering Problem) while allowing parameter customization to adapt to various real-world scenarios.
## Pheromone:
- In ACO, pheromone is used to store and share information about the quality of routes among the ants.
- The amount of pheromone on an edge indicates the level of attraction that edge has for other ants.
- The higher the pheromone level, the greater the likelihood that the edge will be selected in subsequent iterations.
## Routing plan: 
In MMACO, ants build routes for ThOP by following pheromone trails, choosing nodes based on pheromone levels and rewards. The Max-Min rule keeps pheromone balanced, guiding ants to explore diverse paths.
## Packing plan:
Ants in MMACO pack the best nodes into routes, using pheromone to select and order them, maximizing rewards within constraints.
## Local Search:
- Local Search is an optimization technique aimed at improving an existing solution by making small changes to the route, with the hope of finding a better solution in the neighborhood of the current one.
- The algorithm determines whether to activate local search based on criteria such as the number of iterations, profit threshold, or random probability.
Common local search methods include:
- 2-opt: Swaps two edges in the route to create a new route with a shorter length.
- 3-opt: Replaces three edges in the route to find a more optimal structure.
- Swap: Exchanges the positions of two cities in the route to improve it.
## Result:
![image](https://github.com/user-attachments/assets/1ac7f2d4-dc8b-4235-93fe-cd3258a2bd53)

## Demo:
![demo (1)](https://github.com/user-attachments/assets/1acd4655-5041-4e23-98a3-976be740dec1)

