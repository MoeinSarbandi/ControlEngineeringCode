# Analyzing the Impact of Sampling Time on System Response

Welcome to this repository, where we provide MATLAB code to analyze the effect of different sampling times ($dt$) on the step response of a discretized system. The continuous-time system we begin with is described by the open-loop transfer function:

$$ G(s) = \frac{12}{s^2 + 3s} $$

Our objective is to obtain the step response of the discretized system using Euler's approximation and visualize how varying the sampling time affects the system's response.

## System Overview

- We start with an unstable continuous-time system.
- Our initial task is to stabilize this system by designing a suitable controller.

## Code Highlights

We utilize MATLAB to perform the system analysis and visualize the impact of various sampling times. The primary steps in the code are as follows:

1. Definition of the continuous-time open-loop transfer function and plotting its step response.
2. Creation of a closed-loop transfer function and its conversion to state-space representation.
3. Specification of the simulation time and an array of different sampling times ($dt$).
4. Generation of the step response for the continuous system.
5. Application of Euler's approximation for discretization and calculation of the step response for each sampling time.
6. Plotting and comparison of the Euler approximations for different sampling times with the continuous-time response.

## Instructions for Use

To utilize this code, please follow these steps:

1. Clone or download this repository to your local environment.
2. Launch MATLAB and navigate to the directory where you saved the code.
3. Execute the MATLAB script.
4. Observe the generated plots that demonstrate the influence of various sampling times on the system's step response.

## Analysis Results

The provided code generates several plots that vividly illustrate the step responses of the discretized system for different sampling times. These plots allow you to witness how the discretized system approaches the behavior of the original continuous-time system as the sampling time decreases.

## Example Plots

<p align="center">
  <b>Continuous-Time Step Response (Open-Loop System)</b><br>
  <img src="https://github.com/MoeinSarbandi/ControlEngineeringCode/blob/main/Sampling-Time-Impact-Analysis/1.png" width="400" height="300" />
</p>

<p align="center">
  <b>Continuous-Time Step Response (Closed-Loop System)</b><br>
  <img src="https://github.com/MoeinSarbandi/ControlEngineeringCode/blob/main/Sampling-Time-Impact-Analysis/2.png" width="400" height="300" />
</p>

<p align="center">
  <b>Euler Approximation Step Responses (Various Sampling Times)</b><br>
  <img src="https://github.com/MoeinSarbandi/ControlEngineeringCode/blob/main/Sampling-Time-Impact-Analysis/3.png" width="700" height="400" />
</p>

<p align="center">
  <b>Comparison of Euler Approximations with Continuous Response</b><br>
  <img src="https://github.com/MoeinSarbandi/ControlEngineeringCode/blob/main/Sampling-Time-Impact-Analysis/4.png" width="700" height="400" />
</p>




Please refer to the corresponding figures in the code for more detailed visuals of the results.

Explore and gain insights into how different sampling times impact system responses!
