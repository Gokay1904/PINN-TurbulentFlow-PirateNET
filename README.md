# Estimation of Turbulent Flow Using Physics-Informed Neural Networks (PINNs)

## Overview
This repository contains code and datasets for estimating turbulent flow using **Physics-Informed Neural Networks (PINNs)**. The project focuses on solving the **Navier-Stokes equations** for **fluid dynamics** and modeling **velocity fields** around **periodic hills** using **PirateNET**, a specialized deep learning framework. The study aims to demonstrate the integration of **physical laws** into **neural networks** for accurate turbulence modeling.

## Purpose
- Solve the **Navier-Stokes equations** for fluid flow simulations.
- Use **PINNs** to model complex phenomena in **fluid dynamics**.
- Compare the performance of **PirateNET** against traditional methods like **Multi-Layer Perceptrons (MLPs)**.
- Validate model predictions using key metrics such as **L2 loss** and **L2 accuracy scores**.

## Key Methods
- **Physics-Informed Neural Networks (PINNs)**: Integrating physical principles (Navier-Stokes) directly into the training process.
- **PirateNET**: Residual adaptive network used for fluid dynamics modeling.
- **Optimization**:
  - **Adam Optimizer**: Used for training the model.
  - **L-BFGS Optimizer**: Employed for fine-tuning.
- **Accuracy Evaluation**:
  - **L2 Loss**: A common metric to measure model accuracy.
  - **L2 Accuracy Scores**: Used to assess model's ability to predict velocity fields.

## Data
- The dataset includes **simulated fluid dynamics data** based on **turbulence models**: **k-ε**, **k-ω**, **k-ε-ϕt-f**, **k-ω SST**.
- Focus on the **periodic hills** configuration for turbulence modeling.

## Applications
- **Computational Fluid Dynamics (CFD)**: Solving complex flow simulations.
- **Physics-Informed Deep Learning**: Integrating physical laws into AI models.
- **Turbulence Modeling**: Predicting and analyzing turbulent flows with deep learning.
- **Data Efficiency**: Reducing the need for large datasets by incorporating physics.

## Keywords:
**Physics-Informed Neural Networks (PINNs)**, **PirateNET**, **Navier-Stokes Equations**, **Fluid Dynamics**, **Turbulence Modeling**, **Velocity Fields**, **Deep Learning**, **Artificial Intelligence (AI)**, **Optimization**, **Adam Optimizer**, **L-BFGS Optimizer**, **Residual Networks**, **L2 Loss**, **L2 Accuracy Scores**, **Turbulence Models**, **k-ε**, **k-ω SST**, **Computational Fluid Dynamics (CFD)**, **Data Efficiency**, **Machine Learning**, **Physics-Informed Deep Learning**, **Simulation Data**, **Turbulent Flow Prediction**.
