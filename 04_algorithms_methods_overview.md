This course contained some really amazing and practical contents, I will list the ones that will be stuck in my mind:

# DFS:
When searching through states, going deeper is the priority. If all states in a particular branch are visited,the states on the fringe are next.

# BFS:
Similar to DFS but with the breadth. While DFS can be seen as a stack, BFS is a queue.

# UCS:
Uniform cost search which is similar to the other two but has a priority queue recording the cost. This cost prioritizes which one state is visited next.

# Greedy search:
When knowing the heuristics, one can act greedily and take the next step to where the highest heuristic is. However, this relies heavily on the heuristics and will probably not give the optimal answer.

# A star: 
adding a little intelligence to greedy search, A star relies both on the heuristic and the backwards cost similar to UCS. While some call this artificial intelligence, I personally have seen smarter algorithms!

# Adversarial search:
when two agents are competing with each other, things change. Namely, their relative intelligence affects the outcome. In adversarial search each agent tries to beat the other one in being optimal.

# Minimax:
In adversarial search, if both agents act optimal, the one that goes first anticipates the future actions of the opponent and forsees that the opponent will try to minimize their score and they try to maximize it.

# Expectimax:
minimax but giving room to the opponent to make mistakes. The opponent might not be that intelligent, so the minimum rewards might not always be what the agent gets.

# Minimax Pruning:
the agent does not need to explore opportunities that are higher than the least minimum of the branches.

# Alpha beta pruning:
this type of pruning prunes away branches that will not affect the final decision, making it easier to perform minimax.

# Markov decision process:
adding a transition state after the action has been taken, this process maps out the possibilities and rewards of taking actions from different states.

# Value iteration:
in order to find out the V in the markov decision process, value iteration plays many games and record what was achieved in the end when starting from one state and going in a direction. The more it plays the better understanding of the expected values it gains.

# Reinforcement learning:
this type of learning can perform well even if the markov decision model is not present. RL uses experiences learnt from each action to find the right Q values and therefore optimal policies.
