## Introduction:
Gradient Descent is an iterative optimization algorithm used for finding the minimum of a function. It's commonly employed in machine learning to minimize the cost function associated with training a model

## Algorithm:
- Start with initial values for the parameters θ
- Calculate the gradient of the cost function J(θ) with respect to each parameter θ<sub>i</sub>
- Adjust the parameters in the opposite direction of the gradient to minimize the cost.
  θ<sub>i</sub> = θ<sub>i</sub> − α<sup>*</sub>∂J/∂θ<sub>i</sub> <br> α is the learning rate, controlling the size of the steps taken
- Iterate steps 2-3 until convergence or a specified number of iterations.

## Challenges:
- Choosing the Learning Rate: Too high may cause overshooting, too low may lead to slow convergence.
- Local Minima: The algorithm may get stuck in a local minimum and not find the global minimum.
​	
 
​	
 
​	
 
