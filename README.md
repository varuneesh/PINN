# Physics Informed Neural Networks
Physics Informed Neural Networks(PINNs) are neural networks that are trained to solve supervised learning tasks while respecting any given laws of physics described by non linear differential equations.
## Aim
In this project aim was to train an artificial neural network on supervised data that also followed a given non linear differential equation.
## Model
To incorporate the information provided by the differential equation, I modified the loss function used to train the neural network. This modification involved adding the mean square error to the given differential equation. Since all data points should satisfy this equation, minimizing the loss function ensures that the points satisfy the differential equation, ultimately providing us with a solution to it.
