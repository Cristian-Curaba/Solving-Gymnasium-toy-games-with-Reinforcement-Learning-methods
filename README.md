# Project for reinforcement learning course at "Data Science and Scientific Computing" master degree in Units.

Goal: solving toy games from Gymnasium (openAI) package with algorithms implemented from scratch.
 
Algorithms: q-learning, sarsa, expected sarsa, constant rate Monte Carlo.

Toy games: Blackjack, Cliff Walking, Frozen Lake, Taxi.

Contents:
    Expected_SARSA.ipynb, Constant_Rate_Monte_Carlo, Q_learning.ipynb, SARSA.ipynb contains the realative algorithm with everything needed to test them in each environment.

    Everything.ipynb, Analysis.ipynb are auxiliar Jupyter Notebook to make a grid tuning and confront the solutions.

    Best_*game_name* folders contain the tuned algorithm for solving each game.

    others_*game_name* folders contain all the discarded plots from the tuning grid process.

    policy_*game_name* folders contain gifs (20 images) to show the policy learned by the two best algorithms for each game (they are always q-learning and sarsa). policy_blackjack folder contains also grid plots to better understand differences between policies.

    Report.pdf is the presentation for the exam (use Adobe Reader to visualize gifs).