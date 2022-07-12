# VI Gauss' s Law
## 1: Flux
### 1.1 An intuitive example
  The flux will be the same through the ends as through same imaginary cross section in the middle.
### 1.2 Definition
Some imagined aera perpendicular to the field direction. This is the flux, $\varphi$.
(like several arrows across the aera).
## 2. Gauss's Law
### 2.1 Formula
The amount of the **displacement field** flux passing outward through a closed surface is equal to the amount of the **charge inside** the closed surface.

i.e.
$$
\varphi_D=\int_s\vec{D}\quad d\vec{A}=\int_V\rho\quad dV=Q
$$
### 2.2 Example for the point charge
Imagine a Gaussian surface "S" (sphere centred on the charge)
By the symmetry,$\vec{D}$ and $d\vec{A}$ must be parallel.
$$
\int_S\vec{D}d\vec{A}= \int_SDdA
$$
So 
$$
\varphi_D=D.4\pi r^2=Q
$$
$$
D=\frac{Q}{4\pi r^2}
$$
### 2.3 Important considerations
* Applied to any surface and distribution.
* No charge does not mean no field ,just means leaves is equal to the enters.

### 2.4 Process to follow
* Identified symmetry
* Choose suitable Gauss surface(make it so that the field is parallel or perpendicular to it)
### 2.5 Application to a plane of charge
#### 2.5.1
Imagine an infinite plane and we add a proton on the plane.
**We can now define a uniform positive areal charge density, $\sigma$**
#### 2.5.2
A cylinder of radius $r$
 and total height $2h$
 bisected by the plane of charge is a **suitable Gauss surface**.
 #### 2.5.3
 Divide the surface integral into regions:
 $$
 \int_S\vec{D}d\vec{A}=\int_{top}\vec{D}d\vec{A}+\int_{side}
\vec{D}d\vec{A}+\int_{bottom}\vec{D}
d\vec{A} 
$$
$$
\int_{side}
\vec{D}d\vec{A}=0
$$
$$
\int_{top}\vec{D}(h)d\vec{A}=\int_{bottom}\vec{D}(h)d\vec{A}=D(h)\pi r^2
$$
$$
\int_V\rho dV=\int_S dA=\sigma A
$$
So 
$$
\rightarrow Q=\sigma \pi r^2
$$
To summarize,
$$
2\pi r^2D(h)=\pi r^2\sigma
$$
$$
D(h)=\displaystyle\frac{\sigma}{2}
$$
$$
i.e.D=\displaystyle\frac{\sigma}{2}
$$
**We can find D is independent of distance from the plane.**
### 2.5.40
We can also find the $E$ in this way.
$$
E=\displaystyle\frac{\sigma}{2\varepsilon}
$$
2021.1.14

