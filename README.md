<h1 align="center">RoverBot</h1>
 <p align="center"> <img src="" title="RoverBot "><br> RoverBot</p> 


<h1 align="center">Abstract</h1>
Our roverbot project is a mobile robot based on mecanum wheels that uses a labyrinth
algorithm to plan the shortest path to reach the destination while avoiding obstacles. The algorithm
uses a matrix to represent the labyrinth, where each cell is numbered based on its distance to
the destination. The destination itself is marked with a "0", adjacent cells are marked with a "1",
cells next to cells marked with "1" are marked with "2" and so on until all cells are filled. Then,
the robot is placed in a random cell and uses this matrix to plan its path while marking each cell
it has passed for mapping. This approach allows the robot to navigate efficiently in complex
environments by using distance information and avoiding obstacles to reach its destination
optimally
