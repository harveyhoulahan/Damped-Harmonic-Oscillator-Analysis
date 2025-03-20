**Mathematical Modelling and Simulations: The Damped Harmonic Oscillator Analysis**

**Author: Harvey Houlahan**
**Date: 26/03/2025**

Overview
This repository contains a Jupyter Notebook for FIT3139 Assignment 1. The assignment focuses on numerically estimating a real-world phenomenon – in this case, the behavior of a damped pendulum modeled by a damped harmonic oscillator function:

$\theta(t) = \theta_0 \, e^{-\gamma t} \cos\left(\sqrt{\omega^2 - \gamma^2}\,t\right)$

This model captures both the exponential decay (via the $e^{-\gamma t}$ term) and the oscillatory behavior (via the cosine term) of the system.

The assignment is divided into the following parts:

Part 0: Problem Selection – Describes the chosen model and explains the variables.
Part 1: Exact Solution – Plots the exact function over a domain and shows how changing the exogenous variables ($\gamma$ and $\omega$) affects the system.
Part 2: Introducing Modelling Errors – Implements a Taylor series approximation (truncated after the first two nonzero terms) to simulate limited computational capability, and compares the approximation with the exact solution.
Part 3: Introducing Data Errors – Simulates limited numerical precision by chopping floating point values to 3 decimal places, then compares these results with the high-precision outputs.
Part 4: Total Error – Combines the modelling and data errors to assess the overall impact on the output.
Part 5: Sensitivity and Conditioning – Computes and compares the condition numbers (both exact and approximate) to analyze the sensitivity of the model’s output.

File Structure
FIT3139_Assignment_1.ipynb:
The main Jupyter Notebook containing the code and explanations for the assignment.

README.md:
This file providing an overview, instructions, and details about the Mathematical Modelling and Simulations assignment.
