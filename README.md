# Deep-Learning-for-PDEs-in-Engineering-Physics
Physics Informed approach for applied PDEs problems in Engineering Science in 4 Major Areas

1. Problem A: Recovering Young’s modulus in 1D Elastostatics with help of PINN
2. Problem B: Solving for Pressure Field in 2D Heterogeneous
Porous Media with the help of PINN
3. FNO for Surrogate Modeling for Steady-State Heat
Conduction in Heterogeneous Materials
4. Problem D: Prediction of Traffic Flow Based on Burgers’ Equation Model with the help of CNN surrogate model

*The datasets is available in .h5 format and the same can be downloaded from [text](https://www.kaggle.com/datasets/yhzang32/dno4pdes)

* There are some saved model for the same code in folder models.

* There might be kernel dying issue with some users if using jupyter lab, it is recommended to switch to CPU or import os at top of the code for each problems.

* The figure and error values change slighty in each run depending on intialization of unknows at the start but are not significant.

* The approach for the first problem may not give best results with PINN , it is recommended to switch to PINO in that case.

* AS of now NO test cases have been included and will be included in future.
