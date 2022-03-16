# Supervised-learning
The first problem is a regression task. The aim is to train a neural network to approx-
imate an unknown function: f in which training points are afflicted by some
noise:
 y = f(x) + noise
I decided to study different type of optimizers, loss functions and activation functions in
order to be able to understand what are the ones that fits better in this type of problem.
Due to the small dimension of the training dataset, hyperparameters are tuned using a
grid search, I also use a k-fold cross-validation strategy.

In the second problem we have a simple image recognition problem, where the goal is to correctly classify
images of handwritten digits (MNIST).
Since this time there are 60000 initial data with only 10 possible feature, i decide to split
the dataset in a training dataset (80% on initial dataset) and a validation dataset (20%)
without the KFold cross validation strategy.
I divide my notebook in two section, one is for the fully connected neural network, one for
the convolutional neural network. In the first section I investigate using a grid search the
best activation function and the number of hidden unit. For both I insert a subsection
in which I analyze results with plots and graph.
