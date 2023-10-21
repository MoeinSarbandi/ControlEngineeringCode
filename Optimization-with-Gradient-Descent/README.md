# Gradient Descent for Convex Optimization

Welcome to the Gradient Descent for Convex Optimization repository. This MATLAB code demonstrates the application of gradient descent to optimize a sample convex objective function. 🚀

## Objective

The primary objective of this code is to showcase the application of gradient descent to solve a specific convex optimization problem. The objective function we aim to minimize is represented as follows in LaTeX style:

$$
\displaystyle \text{objective} = (4x(1) - 7)^2 + (0.6x(2) - 2)^2 + 3(x(3) + 4)^2 + 12
$$

## Method

We employ the gradient descent method to minimize the objective function. The process involves:

- Initializing optimization parameters.
- Iteratively executing gradient descent.
- Utilizing backtracking line search to determine appropriate step sizes.
- Tracking and storing objective values at each iteration.

## Results

Upon running the code, you can expect the following results:

- The number of iterations required for convergence using gradient descent: 180.
- The optimal solution, which minimizes the objective function: (1.750, 3.332, -4.000).
- The optimal value of the objective function: 12.000000.

Additionally, the code provides visual representations of the optimization process through plots that illustrate the progression of the objective function value over iterations and the evolution of the solution variables x1, x2, and x3. 📈

![Result Image 1](https://github.com/MoeinSarbandi/ControlEngineeringCode/blob/main/Optimization-with-Gradient-Descent/obj.png)

![Result Image 2](https://github.com/MoeinSarbandi/ControlEngineeringCode/blob/main/Optimization-with-Gradient-Descent/xs.png)

Feel free to reach out if you have any questions or suggestions. Happy optimizing! 😃
