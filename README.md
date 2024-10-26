# CS370-Qlearning-Maze-Pathfinder

A reinforcement learning model built using Tensorflow and Keras libraries trained to solve a 2D maze using a Q-learning algorithm
(Michael Lorenz, 10/26/2024, CS370 SNHU)

## REFLECTION

### Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

To implement a Q-learning algorithm and train an agent to solve the maze, I was given supporting classes TreasureMaze, representing the maze environment with supporting functions for rewards and actions, and GameExperience, used to store game states as episodes and retrieve episodes for learning. Additionally, I was given supporting code in TreasureHuntGame.ipynb that builds the initial maze object and environment, actions dictionary, supporting variables, and deep neural network model that I can use to code the Q-learning algorithm. Using the supporting code and pseudocode that outlined the structure of the algorithm, I implemented a complete training loop that allows the agent to solve the maze by choosing actions through exploration or exploitation, recording its experiences, and updating the model using the neural network in each complete maze game. The agent utilizes states and rewards to refine Q-value predictions, representing the predicted culmination of rewards for each action, and continually trains while refining the network until achieving an average 100% maze completion rate across a specified number of consecutive games.

### Connect your learning from throughout this course to the larger field of computer science:

  #### What do computer scientists do, and why does it matter?
  
  This project aligns with the fundamentals of what computer scientists do--solving complex problems by designing, developing, and analyzing algorithms. In this project, I leveraged data from a maze environment and a reinforcement learning algorithm to design an intelligent agent that solves the problem of solving mazes autonomously. By creating algorithms such as the one I implemented, computer scientists contribute to impactful fields such as artificial intelligence and improve the efficiency and problem-solving capabilities across these fields. 
  
  #### How do I approach a problem as a computer scientist?
  
  As a computer scientist, I use problem-solving techniques to solve problems algorithmically. For this project, I used the components that break the problem into smaller pieces or tools that I can use together to achieve my goal of creating a pathfinding AI. These components include the maze environment object that defines the problem space and the experience object to manage the agent's memory. I also took advantage of the Keras library using the sequential neural network model to utilize the environment and experience components to refine the algorithm and achieve a successful outcome. Using an iterative process, I optimized learning by experimenting with the values of parameters such as the exploration vs exploitation ratio. 

  #### What are my ethical responsibilities to the end user and the organization?
  As a contributor to the field of computer science and software development, it is my ethical responsibility to ensure that my contributions do not unintentionally cause harm to the end user and organization and are not biased. Especially in the field of artificial intelligence, it is important to maintain transparency about the decision-making processes and how the end-user data is used. It is necessary to ensure the security and privacy of user and organization data. In neural networks such as this project, I must ensure the agent does not adopt harmful or biased behaviors. 
