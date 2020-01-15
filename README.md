# Optimization Techniques in Gradient Descent using NumPy.

In this project,We demonstrate the performance of the following optimization techniques used for 
Gradient Descent in Neural Networks by training a 2 layer FF network on Fashion MNIST dataset.

## 1. Base case with no Momentum
We measure the performance of the network without any opimization and measure its performance.
We use this measure as base case.

## 2.Polyak's Momentum
This is classical momentum technique where the current gradient is combined with an 
weighted average of previous gradients for computing the parameters.The method is also refered sometime as 'Heavy ball method'.

## 3.RMSProp (Root Mean Square Propogation)
RMSProp uses exponential average of square of the past gradients for computing the parameters.
This works particularly well compared to classical technique.

## 4.AdaM(Adaptive Moment Optimization)
ADAM is widely used technique of optimizing gradient.It uses the combination of RMSProp and 
classical gradient technique. It uses squared gradients to scale the learning rate and uses moving 
average of the past gradients for computation.




