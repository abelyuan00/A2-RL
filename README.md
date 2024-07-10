This repository is meant for solving a bellman equations explicitly problem.

Explanation of the Problem
The given problem is a reinforcement learning task set in a 5x5 gridworld environment. The grid consists of 25 cells, each representing a possible state. An agent in this environment can move up, down, left, or right. If the agent attempts to move off the grid, it remains in the same position and receives a penalty.

Special states in the grid:

Blue Square (Top-left): Any action yields a reward of 5 and moves the agent to the red square.
Green Square (Top-right): Any action yields a reward of 2.5 and moves the agent to either the yellow square or the red square with equal probability.
Red Square (Center): No special behavior.
Yellow Square (Bottom-right): No special behavior.
Rewards:

Moving off the grid: -0.5
Moving from one white square to another: 0
Moving from special squares (blue, green) as described above.
Tasks:

Estimate the value function for each state using:
Solving the Bellman equations explicitly.
Iterative policy evaluation.
Value iteration.
Determine the optimal policy for the gridworld problem using:
Explicit solution of the Bellman optimality equation.
Policy iteration with iterative policy evaluation.
Policy improvement with value iteration.
