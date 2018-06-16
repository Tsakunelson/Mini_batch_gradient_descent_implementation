# Mini_batch_gradient_descent_implementation
Implement Mini batch gradient descent using a data-set of independent and target points 

Given a dataset of 2 - Dimensional points (x,y coordinantes) as a csv file, Mini batch gradient descent is implemented

Advantages of Mini batch over Stochastic gradient descent
- Splits the datasets into small groups adaptable for learning
- At each iteration, the weights are updated and the model learns better, compared to stochastic gradient descent where the weights are just learned once.

The gradient descent step is calculated using the Mean Square Error (good for differenciation)
