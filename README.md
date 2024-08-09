
# Reinforcement Learning: Gridworld Policy Learning and Value Function Approximation
## Overview
This repository contains the code and analysis for a reinforcement learning assignment focused on two key problems:

Policy Learning in a Gridworld: Using SARSA and Q-Learning to learn optimal policies in a gridworld with obstacles and penalties.
Value Function Approximation in a Random Walk: Comparing the accuracy and efficiency of Gradient Monte Carlo and Semi-Gradient TD(0) methods against the exact value function computed via dynamic programming.
Each part has been implemented in a single combined script for ease of use and to streamline the process of running the analysis and generating the results.

# Repository Structure
## Part1 - Policy_learning: Q_Learning_Sarsa.ipynb
Combined Python script implementing both SARSA and Q-Learning algorithms, generating the policy trajectory plots, and the sum of rewards per episode.
Simply run the script, Q_Learning_Sarsa.ipynb and it  will:

Implement both the SARSA and Q-Learning algorithms.

Generate and save the policy trajectory plots for both methods.

Generate and save the sum of rewards per episode plot.

# Part 2: Value Function Approximation in a Random Walk: Monte_Carlo_n_TD(0).ipynb
Combined Python script implementing the exact value function calculation, Gradient Monte Carlo, and Semi-Gradient TD(0) methods, and generating the comparison plots.
result

python part2_value_function_approximation.py
By runningscript, Monte_Carlo_n_TD(0).ipynb, it will:

Compute the exact value function using dynamic programming.

Compute the value function using the Gradient Monte Carlo method.

Compute the value function using the Semi-Gradient TD(0) method.

Generate and save the comparison plots between the exact, Monte Carlo, and TD(0) value functions.

# Results and Analysis
## Part 1: Policy Learning
SARSA vs. Q-Learning: The policy trajectories and reward plots provide insights into the differences between SARSA and Q-Learning. SARSA’s on-policy nature leads to a more cautious policy, while Q-Learning’s off-policy updates result in a more aggressive strategy. The sum of rewards plots highlight the stability and effectiveness of Q-Learning in finding an optimal path.
 ## Part 2: Value Function Approximation
Exact vs. Approximate Methods: The comparison of value functions reveals that while the Gradient Monte Carlo method closely approximates the exact value function, the Semi-Gradient TD(0) method tends to smooth out the values, leading to underestimation in certain areas. These results underscore the trade-offs between accuracy and computational efficiency.

# Requirements

To run the code in this repository, you need to have the following Python packages installed:

Numpy

Matplotlib

Seaborn

Python

# Contribution

If you would like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request. Contributions that improve the accuracy, efficiency, or functionality of the code are highly appreciated.

# License
This project is licensed under the MIT License. See the LICENSE file for more details.

