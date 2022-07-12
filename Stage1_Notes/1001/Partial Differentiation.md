# VII: Partial Differentiation
## 1: Concept and first Derivative
### 1.1 The concept
* Many quantities are functions of more than one varieties.
* Partial differentiation means finding the gradient as we change one variable whilst others fixed.
### 1.2 Examples
* $h=yx^2$ ($y,x$ both variables):
as we move in the $x$ direction, we can find $\frac{\partial h}{\partial x}=2yx$ or $\frac{\partial h}{\partial x})_y=2yx$, we can say this:"partial dh by dx".
* We also need use the chains rules and product or quotient rules to find the answers.
## 2: Second derivative
### 2.1 Definition
* The ways to produce a second derivative.
   * $\frac{\partial^2 z }{\partial x^2 }=\frac{\partial }{\partial x}(\frac{\partial z}{\partial x})$
   * $\frac{\partial^2 z }{\partial x \partial y }=\frac{\partial }{\partial x}(\frac{\partial z}{\partial y})=\frac{\partial }{\partial y}(\frac{\partial z}{\partial x})$(The order doesn't matter)
### 2.2 Stationary points
* There is a variety of behavior of such functions called saddle points and local max or min points.
* At a stationary point, all first derivation are 0:
$\frac{\partial f}{\partial x}=0$ and $\frac{\partial f}{\partial y}=0$.
* What's more, we need all second derivatives.(The mixed derivation needed to ensure a correct conclusion).
## 3: Small increments:
### 3.1 One variable
* We can use the current slope to estimate the increment of y if the x is fairly small.
* This could also be used as a basis of Newton-Raphson Method and the derivation of engineering theories.
* For example, the change in height $\approx$ distance $\times$ slope, hence :
$$
\delta \approx \displaystyle\frac{dy}{dx}\delta x 
$$
* Example:
   * If the radius of the sphere increases from 0.2m to 0.21m, estimate the change in volume.(Just as an example): $V=\displaystyle\frac{4}{3}\pi r^3$, $\delta\approx\displaystyle\frac{dV}{dr}\delta r=4\pi r^2\delta r=0.0016\pi$, note that the surface area gives the rate of change of volume as the radius increases.
### 3.2 Multiple variables
* For multiple variables,the approach is the same, but with increments resulting from changes in any or all of the variables:
$$
\delta z\approx\displaystyle\frac{\partial f}{\partial x}\delta x+ \displaystyle\frac{\partial f}{\partial y}\delta y
$$
* Example:
   * Estimate the percentage change in volume of a circular cylinder if the length increase in 2% and the radius decreases by 1%:
   $$
   V=\pi r^2L, \delta \approx\frac{\partial V}{\partial r}\delta r+\frac{\partial V}{\partial L}\delta L=2\pi rL\delta r+\pi r^2\delta L
   $$
   $$
   \displaystyle\frac{\delta V}{V}\times 100\approx 2 \displaystyle\frac{\delta r}{r}\times 100+ \displaystyle\frac{\delta L }{L}\times 100
   $$
   * Thus the volume is approximately constant if the ratio of the lengthening to thinning is 0.5.
   * This ratio is called Poisson's ratio($\nu$) in stress analysis, and it is usually less than 0.5.
* Example 2:
   * The Reynolds Number of a fluid flow combines information about the dimensions, speeds and viscosity to characterise the nature of the flow -laminar, turbulent,etc. It is a dimensionless number(no units).If $U$ is typical velocity, $L$ is a typical dimension, and $\nu$ is the kinematic viscosity , the we define:
   $$
   Re=\displaystyle\frac{UL}{\nu}
   $$
   If $L$ is decreased by 5%, $U$ increased by 3%, and $\nu$ decreased by 4%, estimate the change in $Re$.
   * Same as above, 
   $$
   \displaystyle\frac{\delta Re}{Re}\times 100\approx \displaystyle\frac{\delta U}{U}\times 100+\displaystyle\frac{\delta L}{L}\times 100-\displaystyle\frac{\delta\nu}{\nu}\times 100
   $$
## 4: Partial Differential Equations
(short for PDE)
