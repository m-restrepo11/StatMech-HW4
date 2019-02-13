# StatMech-HW4

Exploring montecarlo simulations and the Doob-Gillespie algorithm.

1. Simulate a process where a player bets in a roulette having 36 red numbers, 36 black numbers and a green number 0
  a) The player has as initial funds $100 and makes a $1 bet winnig $36 with a 1/37 probability and losing $1 with a 36/37 probability.       After 100 games what is the player's empirical fund distribution? What is the mean of such adistribution? Imagine a very large number of   players. What is the averge number of games such that half the players go broke?
  b) How does the previous situation change if the player bets either red or black each round? Recall that in this scenario the player wins   $1 with a probability of 18/37 and looses othewise.
  c) Now consider the following betting strategy: A bet $1 every time the player wins, however if the player looses he doubles the bet
  until winning. After winning he reverts to betting $1. On average what are the funds of the player after a long series of bets?

2. Simulate using the Doob-Gillespie algorithm a store clerk according to the following parameters. \
  a) The costumer arrival probability is 1/5 min between 9:00 and 17:00 and 1/2 min between 17:00 and 19:00.
  b) The clerk attends on average a client every 2 minutes.
  c) If the queue is longer than 10 people the costumers gets bored and leave with a probability of 1/10 min.
  What is the average costumer waiting time?
  How many clients does the store loose every month as a result of not having an extra clerk?
