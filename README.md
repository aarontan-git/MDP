# README

## TO DO LIST
### As of Jan 30th 2020
- Short answer part [] 1 a) - e) ]
- Gridworld.py
    - create a class that replicates the behaviour of the MDP
    - should contain 4 functions
        - one to return the initial state of the MDP
        - one to return a view of all possible states
        - two to return the reward and probability of a transtition, respectively
- policy_evaluation.py
    - Find the value function of policy
    - Can use either an iterative method or solve the system of equations
    - Show the value function you obtained to at least 4 decimals
- value_iteration.py
    - implement value iteration to solve the Bellman equations derived earlier
    - run the algorithm with different discount factor
    - provide a complete analysis of result
        - short answers required
- policy_iteration.py
    - repeat the previous but with policy iteration
- Compare value iteration with policy iteration and answer short answer questions

## Important Information
- Due: Feb. 11, 11:59pm
- ZIP Folder
    - PDF Report
    - Python Code

## Google Doc
https://docs.google.com/document/d/12n1HmnPfUfaclALzc7-_7KPOs3C_5ePQttm47y92aDQ/edit?usp=sharing

## Questions
- Question 1
    - a) Why is this problem an MDP?
        - are we suppose to describe the problem wrt "Sufficient statistic"? = P[St+1 | St] = P[St+1 | S1, S2 ... St]
    - b) what does it mean by "are these the only possible choices?"
        - there are other ways to define "states" (instead of coordinates - can be 0 - 25)
    - e) How to group bellman equations? By what criteria?
        - What we proposed so far is okay
- Question 2
    - function to return initial state?
        - To return a random initial state
    - function to return a view of all possible states
        - return a list of all possible states
    - what is the probability of a transition?
- Policy Evaluation
    - what should be the maximum iteration?

## Useful Links
- https://towardsdatascience.com/reinforcement-learning-rl-101-with-python-e1aa0d37d43b
- https://towardsdatascience.com/reinforcement-learning-implement-grid-world-from-scratch-c5963765ebff
- Python: Policy Iteraiton: https://github.com/dennybritz/reinforcement-learning/blob/master/DP/Policy%20Iteration%20Solution.ipynb