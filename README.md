# Advanced-ML
Repo holding the exercises for the Masters course Advanced Machine Learning

Below will describe the implemented code for each assignment.

In the first assignment we implemented a K-bandit problem in an custom created OpenAI gym Environment. As this was a custom environment, we also implemented a custom step function, which implements a custom sampling method found in the slotMachine class. Following this, we implemented an epsilon-greedy policy for the agent to follow, afterwhich we tested several different epsilon values. The results, both the average rewards and the percentage of optimal actions chosen, have been plotted and used in the analysis for the assignment. This can be found in the folder named Assignment_1.

In the second assignment we implemented a Q-learning, SARSA agent, and Random Agent, where the first two agents used the epsilon-greedy policy and the random agent followed no policy. The focus of this assignment was implementing the update function and testing different hyperparameter values, with a focus on the stepsize and discount value. The agents were tested using a variety of episode counts, afterwhich the data has been pickled for future use. The resuls were once again plotted and used in the analysis of the assignment. This assignment can be found in Assignment_2. 
