# Naive Bayes Algorithm to Predict Data

The Gaussian distribution (or normal distribution) is efficient because the only need is to estimate the mean and the standard deviation from the training data. 

First of all, calculate the probabilities for input values for each class using a frequency. With real-valued inputs, calculate the mean and standard deviation (SD) of input values for each class to summarize the distribution. It means that, in addition to the probabilities for each class, store the mean and standard deviations for each input variable for each class. After that, calculate the standard deviation using it's equation. When making predictions, these parameters can be plugged into the Gaussian PDF with a new input for the variable and in return the Gaussian PDF will provide an estimation of the probability of that new input value for that class. Then plug in the probabilities into the equation to make predictions with real-valued inputs.
