# Gradient Descent for Convex Optimization

Welcome to the Gradient Descent for Convex Optimization repository. This MATLAB code demonstrates the application of gradient descent to optimize a sample convex objective function. 

## Objective

The primary goal of this code is to showcase how gradient descent can be used to solve a specific convex optimization problem. The code aims to minimize the following objective function:

```matlab
objective = @(x) (4*x(1) - 7)^2 + (0.6*x(2) - 2)^2 + 3*(x(3) + 4)^2 + 12;
```
## Method
We employ the gradient descent method to minimize the objective function. Here's a brief overview of the process:

- Initialization of optimization parameters.
- Iterative execution of gradient descent.
- Backtracking line search to determine step sizes.
- Tracking and storing objective values at each iteration.


## Results
Upon running the code, you can expect the following results:

- The number of iterations required for convergence using gradient descent.
- The optimal solution (x1, x2, x3) that minimizes the objective function.
- The optimal value of the objective function.
Additionally, the code provides visual representations of the optimization process through plots that show the objective function value over iterations and the progression of the solution variables x1, x2, and x3.


![Result Image 1](https://github.com/MoeinSarbandi/ControlEngineeringCode/blob/main/Optimization-with-Gradient-Descent/obj.png)
![Result Image 2](https://github.com/MoeinSarbandi/ControlEngineeringCode/blob/main/Optimization-with-Gradient-Descent/xs.png)


