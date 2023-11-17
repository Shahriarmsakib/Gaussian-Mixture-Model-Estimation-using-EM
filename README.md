# Gaussian-Mixture-Model-Estimation-using-EM
**ReadMe - Gaussian Mixture Model Estimation using EM**

## Project Overview

This GitHub project focuses on implementing the Expectation-Maximization (EM) algorithm for estimating the parameters of a Gaussian Mixture Model (GMM). The assignment is implemented using Numpy and Matplotlib, showcasing proficiency in data manipulation, statistical modeling, and visualization.


## Project Structure

- Core implementation of GMM estimation using EM.
- Generation of GMM data for accurate and inaccurate knowledge of the number of components.
- Visualization of convergence plots during parameter estimation.


## Notes

- Avoid using pre-existing GMM functions; implement the GMM generator and EM algorithm from scratch.
- Pay attention to the comments and sections marked TODO for code completion.
- Contribute to the convergence script for a detailed analysis of the estimation process.

## GMM Data Generation

1. Accurate Knowledge of Components:
   - Generates GMM data with three specified components.
   - Utilizes Numpy for random data generation.
   - Displays a scatter plot of the generated samples.

## GMM Estimation with EM

1. Accurate Number of Components:
   - Implements EM algorithm for parameter estimation.
   - Compares estimated parameters with ground truth values.
   - Visualizes true and estimated distributions.

2. Inaccurate Number of Components:
   - Iterates over multiple values for the number of components.
   - Studies and reports observations on parameter estimation.

## Convergence Plots

- Analyzes the progress of the EM algorithm through two convergence plots:
   1. Average Negative Log-Likelihood (NLL) vs. Iterations.
   2. Estimated Parameter Values vs. Iterations.

## Results

- Observe convergence plots to understand the behavior of the EM algorithm.
- Compare estimated parameters with ground truth values for accurate knowledge.
- Investigate the impact of inaccurate knowledge on parameter estimation.

Feel free to reach out if you have any questions or encounter issues during execution.
