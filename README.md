# Physics-Informed Neural Networks for Heat Transfer


In recent years, Physics-Informed Neural Networks[1] have been applied to various types of application tasks. 
This example shows how to train a neural network to predict temperature distributions given new initial and boundary conditions. The neural network was trained using a loss function that includes a data loss component, which measures the discrepancy between the network's predictions and targets derived from finite element simulations, as well as a physics-informed loss component that evaluates the residual of the governing partial differential equation (PDE). 

<img src="https://insidelabs-git.mathworks.com/tfukumot/physics-informed-neural-networks-for-heat-transfer/-/raw/main/ref_images/Results.png" width="720">

The PDE used in the loss function is the transient heat equation:

<img src="https://insidelabs-git.mathworks.com/tfukumot/physics-informed-neural-networks-for-heat-transfer/-/raw/main/ref_images/HeatEquation.png" width="360">


## **How to get started**
To get started, clone this repository and run "Example_pinn.mlx".


## **Requirements**
- [MATLAB &reg;](https://jp.mathworks.com/products/matlab.html)
- [Deep Learning Toolbox<sup>TM</sup>](https://jp.mathworks.com/products/deep-learning.html)
- [Partial Differential Equation Toolbox<sup>TM</sup>](https://www.mathworks.com/products/pde.html)


MATLAB version should be R2024a and later (Tested in R2024a)

## **References**

  [1]  Raissi, Maziar, Paris Perdikaris, and George E. Karniadakis. "Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations." Journal of Computational Physics 378 (2019): 686-707.

## **License**
The license is available in license.txt file in this GitHub repository.


Copyright (c) 2024, The MathWorks, Inc.


