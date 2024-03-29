# Nim AI using Q-Learning
In the game of Nim, players take turns removing objects from piles, with the goal of forcing the opponent to take the last object. In this project, we'll build an AI that learns to play Nim using reinforcement learning, specifically Q-learning. The AI will play against itself repeatedly, learning from its experiences to improve its strategy over time.

# Understanding the Code
nim.py

Nim Class: Represents a game of Nim. The class provides methods for initializing the game, determining available actions, switching players, and making moves.

nim_ai.py

NimAI Class: Represents the AI player that learns to play Nim using Q-learning. It contains methods for updating Q-values, choosing actions, and training the AI.

train Function
Trains the Nim AI by simulating games against itself and updating Q-values based on the outcomes.

play Function
Allows a human player to play a game of Nim against the trained AI.

# Implementation Details
States: Represented as the current size of all piles.

Actions: A pair of integers (i, j), representing the action of taking j objects from pile i.

Q-Learning: Q-values are updated based on rewards received for actions and estimates of future rewards.

Epsilon-Greedy Algorithm: Balances exploration and exploitation by selecting actions greedily or randomly.

# To Run the Project
Open a terminal or command prompt in the project directory.

python play.py

--
Made for CS50 AI
