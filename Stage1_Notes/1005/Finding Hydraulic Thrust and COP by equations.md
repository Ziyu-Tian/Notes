# VI Finding Hydraulic Thrust and COP by Equations
## 1. Finding the Hydraulic Thrust by equations
If we let each piece of area of the surface is $dA$ and a small force is $dF$, and $x_0$ be the distance from the 0-0 axis to the COP, we can find:
$$
dF=pdA=\rho ghdA
$$
while
$$
h=xsin\theta
$$
If we use the moments balancing:
$$
Fx_0=\sum_A xdF=\int_A
xdF=\int_A x(\rho gxsin\theta dA)=\rho gsin\theta\int_A x^2dA
$$
## 2. Second moment of area
* The second moment of area can be defined as $I_0=\int_Ax^2dA$, x is the distance from dA to the axis x.
* If we use a Cartesian axes, the I about x axis can be expressed as :
$$
I_{xx}=\iint_R y^2dx dy
$$
(As for a small area A, the dA=dx*dy)
So:
$$
Fx_0=\rho gsin\theta I_0
$$
$$
x_0=\displaystyle\frac{\rho gI_0}{F}
$$
* Second moments of area of common shapes
   * Rectangular: $I_g=\displaystyle\frac{bd^3}{12}$
  
   * Triangle: $I_g=\displaystyle\frac{bh^3}{36}$
  
   * Circle:
  $I_g=\displaystyle\frac{\pi d^4}{64}$
  
   * Parallel Axis Theorem:
   $I_o=I_g+\bar{x}^2A$
* Finding COP with second moments of area:
   $$
   y_0=\bar{y}+\displaystyle\frac{I_gsin^2\theta}{A\bar{y}^2}
   $$


  