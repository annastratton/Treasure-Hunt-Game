# Treasure-Hunt-Game
 8-2 Portfolio Submission - CS-370-J7910 Current/Emerging Trends in CS 23EW4

Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

This code imports various libraries and modules such as Keras, NumPy, and Matplotlib. The NumPy array shown here represents an 8x8 maze object. The function 'show' is a helper function that displays a visual representation of the maze object.

The pirate can move in four directions: left, right, up, and down, and is encouraged to explore the environment to find previously undiscovered paths. The exploration factor, epsilon, is set to 0.1, which means for every ten attempts, the pirate will attempt to learn by experience nine times and will randomly explore a new path one time. The 'actions_dict' dictionary and the 'num_actions' variable are used to map the pirate's four actions to numbers 0 to 3.

The 'play_game' function simulates a full game based on the provided trained model. It takes in the trained model, a TreasureMaze object, and the starting position of the pirate, and returns True if the pirate wins and False if the pirate loses.

The 'completion_check' function checks whether the pirate can win any game at all. It iterates through all of the free cells in the maze and checks whether a game can be won from each of those cells by calling the 'play_game' function.

The 'build_model' function builds the neural network model. It has two hidden layers, each with 64 units and a PReLU activation function. The output layer has four units, one for each possible action the pirate can take, and uses a linear activation function. The optimizer used to train the model is RMSprop, and the loss function is mean squared error (MSE).

Connect your learning from throughout this course to the larger field of computer science:
What do computer scientists do and why does it matter?
How do I approach a problem as a computer scientist?
What are my ethical responsibilities to the end user and the organization?

I have come to understand that computer scientists play a crucial role in developing technology that can solve complex problems and automate tasks. Through this course, I have learned that computer scientists design algorithms, write code, and analyze data to create intelligent systems that can learn and improve over time.

To approach a problem as a computer scientist, I have learned to follow a systematic process of problem-solving. This process involves understanding the problem domain, identifying the input and output requirements, selecting appropriate data structures and algorithms, implementing the solution, and evaluating the results. By breaking down the problem into smaller components and analyzing each one, I can develop a solution that meets the desired specifications.

As a computer scientist, I have ethical responsibilities to the end user and the organization. I must ensure that the technology I develop is safe, reliable, and respects the privacy of the user. I must also ensure that my work is transparent, explainable, and free from bias. By following ethical standards and guidelines, I can ensure that my work has a positive impact on society and contributes to the greater good.
