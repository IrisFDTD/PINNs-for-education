# Physics Informed Neural Networks (PINN) for education
Deep Learning for Solving Differential Equations (Educational)
---
This repository aims to provide educational resources and implementations of deep learning techniques for solving differential equations. It serves as a learning hub for understanding the intersection of deep learning and numerical methods in the context of differential equations.

**Features:**
Implementations of various deep learning models tailored for differential equation problem-solving. Interactive Jupyter notebooks illustrating step-by-step solutions to specific differential equation scenarios.
Educational materials, code samples, and documentation to aid understanding. Datasets and examples to facilitate hands-on experimentation and learning. Discussions on best practices and theoretical background to support learners of all levels.

**Topics Covered:**
Introduction to differential equations and their significance in diverse fields.
Deep learning fundamentals and neural network architectures for differential equation modeling. Whether you're a student, researcher, or enthusiast interested in understanding the exciting realm of deep learning applied to differential equations, this repository offers a valuable resource to augment your knowledge and explore practical implementations. 

These codes are provided as a Supplementary material in the paper  *Solving differential equations in physics with Deep Learning: a beginner’s guide*, [European Journal of Physics DOI:10.1088/1361-6404/ad0a9f](https://iopscience.iop.org/article/10.1088/1361-6404/ad0a9f/pdf) or https://doi.org/10.48550/arXiv.2307.11237 by Luis Medrano Navarro $^2$, Luis Martin Moreno $^{2,3}$ and Sergio G Rodrigo $^{1,2}$
+ $^1$ Departamento de Física Aplicada, Facultad de Ciencias, Universidad de Zaragoza, 50009 Zaragoza, Spain, $^2$ Instituto de Nanociencia y Materiales de Aragón (INMA), CSIC-Universidad de Zaragoza, 50009 Zaragoza, Spain, $^3$ Departamento de Física de la Materia Condensada, Universidad de Zaragoza, Zaragoza 50009, Spain
+ *corresponding author: sergut@unizar.es*

**[Example 1: 1st order linear ODE](https://nbviewer.jupyter.org/github/IrisFDTD/PINNs-for-education/blob/main/1st_order_ODE_PINN.ipynb)**
This Jupyter notebook presents the first of the ODEs solved with PINNs in this work:  the exponential decay ODE.

**[Example 2: 2nd order linear ODE](https://nbviewer.jupyter.org/github/IrisFDTD/PINNs-for-education/blob/main/2nd_order_ODE_PINN.ipynb)**
This Jupyter notebook presents the second of the ODEs solved with PINNs in this work:  the harmonic oscillator.

**[Example 3: 2nd order non-linear ODE](https://nbviewer.jupyter.org/github/IrisFDTD/PINNs-for-education/blob/main/2nd_order_nonlinear_ODE_PINN.ipynb)**
This Jupyter notebook introduces the third example of solving ODEs with PINNs in this study: the Korteweg–de Vries (KdV) non-linear ODE.

**Additional work on PINNs**:
+ *[3rd order nonlinear ODE PINN.ipynb](https://nbviewer.jupyter.org/github/IrisFDTD/PINNs-for-education/blob/main/3rd_order_nonlinear_ODE_PINN.ipynb)* has been implemented by Jorge Paz-Peñuelas Oliván (774270@unizar.es) as part of extracurricular activities at the University of Zaragoza in July 2023. The code builds upon the 2nd-order ODE implementation using Physics-Informed Neural Networks (PINNs) done by Luis Medrano.Navarro, Luis Martin Moreno and Sergio G Rodrigo.
+ *[PINN_for_optics_eikonal.ipynb](https://nbviewer.jupyter.org/github/IrisFDTD/PINNs-for-education/blob/main/PINN_for_optics_eikonal.ipynb)* has been implemented in collaboration with Paula Robredo Mexía (775198@unizar.es), this project addresses a classical problem in the field of optics: ray tracing within a Gradient-Index (GRIN) medium. The work was part of a Final Degree Thesis at the University of Zaragoza.
