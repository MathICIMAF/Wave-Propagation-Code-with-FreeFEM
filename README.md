# WavePropagation Code #
**WavePropagation Code** is based on the numerical solution of the wave propagation equations for several selected frequencies in thin isotropic plate. In our approach to solve these equations, the temporal variable is first discretized with a second order different scheme. This leads to partial differential equations that is resolved by **FEM**.

![](/images/Imagen1.jpg)

We study the ultrasonic wave propagation problem, it is assumed symmetry with respect to the z-axis and zero displacement in the z-direction. Therefore, the wave propagation problem is represented as a two-dimensional plane strain model in the x−y plane. Physical damping is not included. The domain Ω of the problem is a finite 2D plate, as shown in the Figure, with boundary ∂Ω = δ1 ∪ δ2 ∪ δ3 ∪ δ4.


## Requirements

**WavePropagation Code** has been tested with FreeFem++ 3.56 and above and should run on most personal laptops and desktop machines.

## Input


**f0** - frequency (Hz). Use a frequency value in the interval [1 , 30]x10^5 Hz.



## Functionality

Some of the code functionality includes:

	Plot the region with the mesh.
	Plot the wave propagation.
	Calculate the displacement values at points (x, y)
	There are 4 files that contain the values ​​of the second component of the displacement evaluated at 4 fixed points.

![](/images/Imagen3.jpg)

	












