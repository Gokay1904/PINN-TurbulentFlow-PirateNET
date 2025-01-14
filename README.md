# PINN-TurbulentFlow-PirateNET

This project uses Physics-Informed Neural Networks (PINNs) to estimate turbulent fluid flow, specifically modeling the velocity fields around periodic hills. It combines neural networks with physical laws to solve fluid dynamics problems, such as the Navier-Stokes equations.

## What is this project?
The goal of this project is to apply PINNs to model and predict fluid behavior (turbulent flow) in various scenarios. The neural network framework PirateNET is used to learn from simulation data while ensuring the model adheres to physical laws. This helps improve the model’s accuracy while reducing reliance on large datasets and high computational costs. The implementation utilizes Adam and LBFGS optimizers in PyTorch to train the model effectively.

## Key Features

- **Physics-Informed Neural Networks (PINNs):** Incorporates physical laws directly into the model to improve predictions in fluid dynamics.
- **PirateNET:** A deep learning framework designed for physics-based neural networks.
- **Optimizers:** The model uses **Adam** and **LBFGS** optimizers to enhance training efficiency, with a comparison of their performance.
- **PyTorch:** The neural network is built using **PyTorch** for flexible and efficient deep learning.
- **Fluid Modeling:** Focuses on predicting turbulent flow and velocity fields in fluid dynamics, specifically around periodic hills.
