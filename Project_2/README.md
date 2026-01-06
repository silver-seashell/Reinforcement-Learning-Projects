# Solving the Frozen Lake Problem using Dynamic Programming

Consider a 4×4 Frozen Lake grid. Some cells are holes (H) and some are frozen (F).

- The robot can move in four directions: left, right, up, and down.
- Reward definitions:
  - Entering a frozen cell (F) : reward = 0  
  - Entering a hole (H) : reward = −1 (episode ends)  
  - Reaching the goal (G) : reward = +1 (episode ends)  
  - Any move that causes the agent to go outside the grid returns the agent to the same cell and gives a -1 reward.

Assume the environment is deterministic.

---

## Tasks

### (a) Policy Iteration

Write a Python program and use policy iteration to find the optimal policy (best path for the robot).

---

### (b) Value Iteration

Write a Python program and use value iteration to find the optimal policy.

---

## Grid Layout

| S | F | F | F |
|---|---|---|---|
| F | H | F | H |
| F | F | F | H |
| H | F | F | G |

