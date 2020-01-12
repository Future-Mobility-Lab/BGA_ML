# BGA_ML
This is a code for the Boosted Genetic Alogorithm by Machine Learing algorithm (BGA-ML).
As a benchmark, we first start with deploying a typical GA algorithm by considering the phase duration as the decision variable and the objective function to minimize the total travel time in the network. We fine tune the GA for crossover, mutation, fitness calculation and obtain the optimal parameters. Secondly, we train various machine learning regression models to predict the total travel time of the traffic network under study. The best regression model is then selected by comparing various performance indicators such as the mean absolute error, root mean squared error, mean absolute percentage error and R-squared; the chosen model is further hyper-tuned to find the optimal training parameters. Lastly, we propose a new algorithm BGA-ML which combines the GA algorithm and the extreme-gradient decision-tree together (best performing regressor) in a single optimisation framework. Comparison and results show that the new BGA-ML is much faster than the original GA algorithm and can be successfully applied under incident conditions.

# Installation
Just download this project and use jupyter note to open: the "Test19_GA_with_ML.ipynb".

# Author
Tuo Mao (UTS)

# Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

#License
No special license. 
