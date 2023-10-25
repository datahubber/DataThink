doubts:
1. How target_encoder generate numbers?
2. Can the predicted result be scaled to get a better score? For esample, if the predicted result is 0.9, but the actual result is 0, the logloss will make a big error score. Scale the predicted result to be 0.7, the logloss will reduce a lot if the actual result is 0, but won't increase a lot if the actual result is 1. It's a trade off between probability and loss.

2023.10.24 lecture 7
1. random_state = 42: 42 is the probability rule of the universe in many myths.
2. Stochastic gradient descent: Use randomness to get the global minimum.
3. Stratification: Deal with imbalanced dataset. Works well on large dataset.
