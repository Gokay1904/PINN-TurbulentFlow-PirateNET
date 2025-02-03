# Estimation of Turbulent Flow Using Physics-Informed Neural Networks (PINNs)

## Project Overview
This project applies **Physics-Informed Neural Networks (PINNs)** to simulate **turbulent fluid flow**, focusing on the **Navier-Stokes equations** and **velocity fields** around **periodic hills**. Using the **PirateNet** framework (Physics-Informed Residual Adaptive Networks), the model integrates **physical laws** with **deep learning** to accurately simulate complex fluid dynamics scenarios.

### Key Concepts:
- **PINNs (Physics-Informed Neural Networks)**: Neural networks that embed physical constraints (such as the **Navier-Stokes equations**) directly into the learning process, making the network more data-efficient and physically accurate.
- **PirateNet**: A deep learning framework for solving physical problems using **Residual Adaptive Networks**. It adapts dynamically to physical laws for fluid simulations.
- **Turbulence Modeling**: The project uses datasets from several turbulence models, including **k-ε**, **k-ω SST**, to simulate different fluid flow conditions, focusing particularly on **periodic hills**.
  
### Optimizers Used:
- **Adam Optimizer**: A widely used optimizer in deep learning for improving convergence during training by adapting learning rates based on past gradients.
- **L-BFGS Optimizer**: A quasi-Newton optimization algorithm that performs better in problems with fewer iterations, useful for highly non-linear models.

### Model Evaluation:
- **Loss Function**: **L2 loss** was used to evaluate the difference between predicted and true values. The optimization process minimizes this loss, ensuring more accurate predictions.
- **Accuracy Metrics**: **L2 Accuracy Scores** were used to assess model performance, measuring how closely the predicted velocity fields match the expected values.

## Project Goals:
- **Physics-Informed Learning**: Investigate the effectiveness of PINNs in **fluid dynamics simulations**, particularly for complex turbulence problems.
- **Comparative Analysis**: Benchmark **PirateNet** against traditional methods, including **Multi-Layer Perceptrons (MLPs)**, to assess improvements in accuracy and efficiency.
- **Velocity Field Modeling**: Use **PINNs** to model the **velocity fields** around **periodic hills**, a common and challenging geometry in turbulence studies.

## Setup and Requirements:
- **Python**
- **PirateNet**
- **TensorFlow** or **PyTorch** (for deep learning frameworks)
- **Pandas**, **NumPy**, **Matplotlib** (for data processing and visualization)

## Results:
The model was trained and evaluated with different configurations:
- **Adam Optimizer**: 8000 iterations with a learning rate of 0.1.
- **L-BFGS Optimizer**: 12000 iterations with a learning rate of 0.05.

### Evaluation Metrics:
- **Model Loss by Iterations**: Plots showing how the loss function decreased over training iterations.
- **Model L2 Accuracy Scores**: Evaluated the model’s performance at each stage, ensuring high accuracy in predicting fluid dynamics.

## Conclusion:
The results of this study indicate that **Physics-Informed Neural Networks** (PINNs), specifically using **PirateNet**, can efficiently model **turbulent flow** and **velocity fields**. The integration of physical laws into the training process helps to improve accuracy, reduce data dependency, and offer a more computationally efficient approach for fluid dynamics simulations.

## Repository:
The complete code and implementation can be accessed in this [GitHub Repository](https://github.com/yourusername/yourrepository).

---

### Keywords:
- **Physics-Informed Neural Networks (PINNs)**
- **PirateNet**
- **Fluid Dynamics**
- **Navier-Stokes Equations**
- **Turbulence Modeling**
- **Velocity Fields**
- **Machine Learning**
- **Deep Learning**
- **Optimization**: **Adam Optimizer**, **L-BFGS Optimizer**
- **Accuracy Metrics**: **L2 Loss**, **L2 Accuracy Scores**
- **TensorFlow**, **PyTorch**
- **Residual Networks**
- **Data Efficiency**
- **Artificial Intelligence (AI)**
- **Computational Fluid Dynamics (CFD)**
- **Turbulence Models**: **k-ε**, **k-ω SST**

