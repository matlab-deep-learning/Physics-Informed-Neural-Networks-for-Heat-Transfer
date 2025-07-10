:warning: Project Archived

This repository is no longer actively maintained.

Development has moved to a new repository, which contains all the content from here and is actively updated with new features and improvements.

➡️ Please visit [physics-informed-neural-networks-for-heat-transfer](https://github.com/matlab-deep-learning/SciML-and-Physics-Informed-Machine-Learning-Examples/tree/main/physics-informed-neural-networks-for-heat-transfer) for the latest version and continued development.

This repository will remain available for existing users, but we recommend switching to the new repository for the most up-to-date experience.

# Physics-Informed Neural Networks for Heat Transfer


In recent years, Physics-Informed Neural Networks[1] have been applied to various types of application tasks. 
This example shows how to train a neural network to predict temperature distributions given new initial and boundary conditions. The neural network was trained using a loss function that includes a data loss component, which measures the discrepancy between the network's predictions and targets derived from finite element simulations, as well as a physics-informed loss component that evaluates the residual of the governing partial differential equation (PDE). 

<img src="https://github.com/matlab-deep-learning/physics-informed-neural-networks-for-heat-transfer/blob/main/ref_images/Results.png" width="720">

The PDE used in the loss function is the transient heat equation:

<img src="https://github.com/matlab-deep-learning/physics-informed-neural-networks-for-heat-transfer/blob/main/ref_images/HeatEquation.png" width="360">


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

## **Open in MATLAB Online**
[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=matlab-deep-learning/Physics-Informed-Neural-Networks-for-Heat-Transfer)

Copyright (c) 2024, The MathWorks, Inc.


