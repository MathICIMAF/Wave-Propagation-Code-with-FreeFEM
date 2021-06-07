# WavePropagation Code

The WavePropagation Code is the FreeFem++ implementation of the numerical solution of the propagation of a pulse along a thin aluminum plate.The partial differential equations modelling the problem are solved discretizing first the temporal variable with a second order difference scheme.For each fixed value of time,this leads to partial differential equations depending only on the spatial variables,which are solved by means of FEM.

The domain Ω of the problem is a finite 2D plate with boundary ∂Ω subdivided in 4 sections:δ1, δ2, δ3 and δ4. Boundaries δ1, δ2, δ3 are free. A pulse g(t) depending on time tand on an input frequency is applied on δ4,

![](/images/Imagen0.jpg)

![](/images/Imagen1.jpg)

![](/images/Imagen2.jpg)

## Requirements

WavePropagationCode has been tested with FreeFem++ 3.56 and above and should run on most personal laptops and desktop computers.

## Input
![](/images/Imagen4.jpg)

## Functionality

	• Calculate the pulse displacement.
	• Plot the wave propagation.
	• Export the values of the vertical component of the pulse displacement at 4 fixed points on the top of the plate and plot the corresponding curves.
## Graphical Output of WavePropagation Code

Pulse displacement at 4 fixed points on the top of the plate.

![](/images/Imagen5.jpg)

Deformation of the plate for a fixed time after emitting a pulse on the boundary δ4.
Colors correspond to the magnitude of the vertical displacement.

![](/images/Imagen3.jpg)

## Next version of the code
Implementation of the Phase Velocity method to compute the phase velocity dispersion curve.


![](/images/Imagen6.jpg)