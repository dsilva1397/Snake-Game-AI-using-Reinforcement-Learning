# Snake-Game-AI-using-Reinforcement-Learning
Using Reinforcement Learning a simple comparison between Hamiltonian cycle and A* Algorithm.


1. Basic model: Just a simple Snake Game with a basic Reward, Action and state.
2. Mathematical model : Hamiltonian cycle.
3. Advanced model: a* Rl technique with Hamiltonian cycle.

* Hamiltonian Cycle: The Hamiltonian Cycle is an algorithm used to solve Maze Games and create a predetermined path in a localized area or set of points. The Hamiltonian Path in this use case is a directed graph that visits a vertice just once but never more than once.

* Advanced Model: This model is derived from the Base model and the Mathematical Hamiltonian Cycle
Here the snake makes decisive decisions and using the A* Algorithm finds the shortest path to the food. Moving is now more diagonal than path following. Hence, the fetching of food is faster in the initial phase. 
When the snake grows larger it begins following the Hamiltonian Cycle to continue.

* Towards the end of our journey, we created one perfect snake using the A* algorithm and the Hamiltonian cycle mathematical model.
With the inclusion of reinforcement learning A* algorithm to take shortcuts and the mathematical model of maze finding we have created safe shortcuts declared that can help the snake take decisions in the initial period and follow the Hamiltonian cycle in the advanced stage to complete the game in a short time possible.
