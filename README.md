# Imitation_Learning

- Lunar Lander game from OpenAI Gym using behavioral cloning, DAgger methods, and POMDP(Partially-Observable Markov Decision Processes)

## Behavioral Cloning (BC):

Behavioral cloning is a straightforward method in imitation learning. In this approach, supervised learning is executed on a provided expert dataset. For discrete actions, we typically maximize log likelihood or minimize cross entropy. For continuous control scenarios, the method involves minimizing the mean-squared error, though maximum likelihood estimation (MLE) is also an option.

## Dataset Aggregation (DAgger): 

DAgger operates as an interactive learning algorithm, enabling us to consult the expert whenever necessary. This interactivity offers the learner more flexibility since it isn't strictly bound by an initial dataset; instead, it can continuously seek expert insights throughout the learning process.

- For DAgger, just as with BC, you'll need to implement the accompanying learn() function.
