# Tic Tac Toe Implementation using Multi Agents
# Introduction

Tic Tac Toe is a classic and engaging two-player game played on a three-by-three grid. Each player alternates placing their symbol, typically 'X' or 'O,' into an empty square, aiming to form a straight line of three symbols either horizontally, vertically, or diagonally. The objective is to create this line before your opponent does. Simple to learn yet rich in strategic possibilities, Tic Tac Toe offers quick and enjoyable gameplay for all ages.

# Implementation

To achieve optimal decision-making, various agents can be utilized, including the Q-learning algorithm for reinforcement learning and the Alpha-Beta and Minimax algorithms for adversarial search. These agents evaluate key parameters such as the number of moves, node exploration, and the total time required to complete the game, striving to make the most effective choices at each step.

<div align="center">
  <img width="450" alt="OIP" src="https://github.com/Chtejareddy10/AI-Final-Project/assets/AlphaBeta.png">
</div>

# Objectives

1. Develop AI agents for both adversarial search and reinforcement learning to play the game of Tic Tac Toe.  

2. Implement three distinct AI agents using the Minimax Algorithm, Q-learning, and Alpha-Beta Pruning techniques.  

3. Evaluate the performance of each algorithm by having the agents play multiple games of Tic Tac Toe.  

4. Assign points to players for forming a line of three consecutive symbols in a row, column, or diagonal.  

5. Identify key metrics to compare the performance of the three algorithms and determine which approach—adversarial search or reinforcement learning—is more effective.  

# Approaches

Our primary strategy for reinforcement learning involves utilizing:  
```
1.Q-Learning.
```
As a complementary approach, we adopt adversarial search, leveraging the following techniques:  
```
1.Minimax Algorithm 
2.Alpha-Beta Pruning.
```
Python 3 is the main component of the technology stack that these techniques rely on.
```
1.Python3

```

# Brief Description of Agents

# Q-Learning

Q-Learning is a popular reinforcement learning technique grounded in the Bellman Equation. The agent aims to identify the optimal actions that maximize rewards by learning from past experiences. At each step, the agent's objective is to improve its decision-making by increasing the "Q-value," which represents the expected performance of specific actions in given states.


# Reinforcement Learing


Reinforcement learning is a machine learning approach where an agent learns through trial and error within an interactive environment. By observing its actions and their outcomes, the agent adapts and acquires knowledge to improve its performance over time.


<img width="500" alt="image" src="[https://github.com/mummadiroshanreddy/AI-Final-Project/assets/129618586/5ae7858b-a421-45d6-bd09-5f8f613c1099](https://www.bing.com/images/search?view=detailV2&ccid=GWCMlTt7&id=20E2237D5677D5177056335E3E59C6AB157D4FE4&thid=OIP.GWCMlTt7tsDoaqK0M2gLHwHaDd&mediaurl=https%3A%2F%2Fmiro.medium.com%2Fv2%2Fresize%3Afit%3A1162%2F1*KBrRlD4jlyeOQMI-usMfIw.png&cdnurl=https%3A%2F%2Fth.bing.com%2Fth%2Fid%2FR.19608c953b7bb6c0e86aa2b433680b1f%3Frik%3D5E99FavGWT5eMw%26pid%3DImgRaw%26r%3D0&exph=542&expw=1162&q=reinforcement+learning+images+for+tic+tac+toe&simid=608003650198662852&FORM=IRPRST&ck=99018933095564EE66330CF2E1B11E1D&selectedIndex=1&itb=0&cw=1145&ch=607&ajaxhist=0&ajaxserp=0)">

# Min-Max Algorithm


The **Minimax Algorithm** is a decision-making method in game theory used for two-player games like Tic-Tac-Toe. It builds a decision tree of all possible moves and recursively evaluates them to find the optimal strategy.  

# Key Points:  

1. Optimization: Alternates between maximizing one player’s score and minimizing the opponent's.  
2. Scoring: Assigns values to outcomes (higher for "X," lower for "O") and chooses the best move.  
3. Exploration: Uses Depth-First Search (DFS) to navigate the game tree.  
4. Challenges: Effective for small grids but computationally expensive for larger, complex games.  

**Enhancements like Alpha-Beta Pruning** help reduce the search space, improving efficiency without sacrificing accuracy.


<img width="450" alt="image" src="https://github.com/mummadiroshanreddy/AI-Final-Project/assets/129618586/c30cda74-0e86-4e31-ad3a-5c82d33d504b">

# Alpha-Beta

Reducing the overall number of nodes in the search tree produced by the min-max algorithm is the main objective of alpha-beta pruning. This method is commonly used in two-player games that make use of adversarial search techniques. When applied to a min-max tree, it produces the same moves as min-max but skillfully eliminates branches that are not important in deciding the ultimate result.

![ai project](https://github.com/mummadiroshanreddy/AI-Final-Project/assets/129618586/27603b60-f5a1-46b4-b5d1-3b54e6a30a1c)


# Deliverables  

1. Documentation:  
   A detailed user guide explaining the Minimax, Alpha-Beta Pruning, and Reinforcement Learning Agents used in Tic-Tac-Toe.  

2. Python Code:  
   .py` files containing the implemented algorithms for the AI agents.  

3. GitHub Repository: 
   A shared URL providing access to the Python code and related resources.  

4. Presentation & Video
   Slides and a YouTube video demonstrating the project’s implementation and key findings.  


# Evaluation Methodology  

To comprehensively assess the AI agents' performance in Tic-Tac-Toe, the following metrics will be considered:  

1. Win Rate:  
   Measures the percentage of games won against specific opponents. Higher win rates reflect better strategic ability.  

2. Average Moves per Game:  
   Tracks the average number of moves required to achieve a win or loss, with fewer moves indicating efficient decision-making.  

3. Training Time:  
   Evaluates how quickly the AI agent learns the game. Shorter training times suggest higher efficiency.  

4. Performance Against Diverse Opponents:
   Tests the agent's adaptability by analyzing its results against opponents with varying skill levels and strategies.  

5. Human-Like Behavior:
   Assesses the agent's ability to mimic human-like gameplay, including strategic planning and countering opponents’ moves, enhancing the gaming experience.  
