![](/images/Imagen3.jpg)

# WavePropagation Code

Companion repository to our paper:

**Title**: *Numerical solution of the wave propagation problem in a plate*

**Authors**: Manuel Cruz Rodriguez, Victoria Hernández Mederos, Jorge Estrada Sarlabous,  Eduardo Moreno Hernández, Ahmed Mansur Graverán

**Abstract**: In this work, the propagation of an ultrasonic pulse in a thin plate is computed solving the differential equations modeling this problem. To solve these equations finite differences are used to discretize the temporal variable, while spacial variables are discretized using Finite Element method. The variational formulation of the problem corresponding to a fixed value of time is obtained and the existence an uniqueness of the solution is proved. The proposed approach leads to a sequence of linear systems with the same sparse, symmetric and positive defined matrix. The free software FreeFem++ is used to compute the approximated solution using polynomial triangular elements. Numerical experiments show that velocities computed using the approximated displacements for different frequency values are in good correspondence with analytical dispersion curves for the phase velocity.


## How to install FreeFem++?

Please, see [here](https://doc.freefem.org/introduction/installation.html) the latest installation instructions for various platforms.

## Disclaimer

This code was tested with **FreeFem++-3.5**.
