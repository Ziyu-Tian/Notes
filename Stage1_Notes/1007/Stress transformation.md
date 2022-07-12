# II: Stress transformation
## 1: Stress at a point
### 1.1: Point stress at a body
* There should be 9 states of stress in a 3D body: 
    * Normal stress: $\sigma_{xx}$,$\sigma_{yy}$ and $\sigma_{zz}$
    * Shear stress: $\tau_{yx}$, $\tau_{yz}$, $\tau_{xz}$, $\tau_{xy}$, $\tau_{zy}$ and $\tau_{zx}$.
* The second subscript means the direction while the first and second means the plane it apply.
* -
* -
* -
### 1.2: Plane Stress
* For convenience, the plane stress is only 2D and is redrawn in x-y plane.
* -
* -
* -
## 2: Uniaxial tension
### 2.1: Definition
* Stresses on an inclined plane, i.e.$\sigma_{yy}=\tau_{xy}=\tau_{yx}=0$
* -
* -
* -
### 2.2: The Transformation equations for uniaxial tension cases
* Cut PQ rotated anti-clockwise through a angle $\theta$ from the vertical 
* Noted that the tension stress is '+' and press stress is '-', for the angle $\theta$, anti-clockwise is '+' and clockwise is '-'.
* -
* -
* -
* Then we can epitomize the stress transformation equations for uniaxial case:
$$
\sigma_{\theta}=\displaystyle\frac{\sigma_{xx}}{2}+\displaystyle\frac{\sigma_{xx}}{2}\cos(2\theta)
$$
and 
$$
\tau_{\theta}=-\displaystyle\frac{\sigma_{xx}}{2}\sin(2\theta)
$$
### 2.3: Failure of ductile and brittle materials
#### 2.3.1: The ductile materials 
* Ductile materials tend fail on planes to the max shear stress.
* According to the sheAR stress equations: $\tau_{\theta}=-\displaystyle\frac{\sigma_{xx}}{2}\sin(2\theta)$, we can fin that the max shear stress occurs at approximately 45 degrees.
* -
* -
* -
#### 2.3.2 The brittle materials
* Brittle material fail due to normal stresses and rupture occurs along a surface perpendicular to the surface.
* To find the transformation of the brittle materials, we should use the formula of $\sigma$, so the max occurs at $\theta =0$ degrees.
* -
* -
* -
### 2.4: General stress transformation equations
* For a more general case with $\sigma_{xx}\ne 0$, $\sigma_{yy}\ne 0$, $\tau_{xy}\ne 0$ and $\tau+{yx}\ne 0$.
* To keep the equilibrium, the shear force and normal stress acting in opposite direction must be equal in magnitude, while the shear stress acting on perpendicular direction must be equal.($\tau_{xy}=\tau_{yx}$)
* -
* -
* -
* Then cut a plane rotated in A/C through an angle $\theta$ from the vertical, there will be $\tau_{\theta}$ and $\sigma_{\theta}$ in the interface to keep the balance.
* -
* -
* -
* The we can get the general stress transformation equations:
$$
\sigma_{\theta}=\displaystyle\frac{\sigma_{xx}+\sigma_{yy}}{2}+\displaystyle\frac{\sigma_{xx}-\sigma_{yy}}{2}\cos(2\theta)+\tau_{xy}\sin(2\theta)
$$
and
$$
\tau_{\theta}=-\displaystyle\frac{\sigma_{xx}=\sigma_{yy}}{2}\sin(2\theta)+\tau_{xy}\cos(2\theta)
$$
## 3: Stress transformation: special cases of plane stress
### 3.1: Case: uniaxial tension
* For the uniaxial tension case, $\sigma_{xx}\not ={0}$ and $\sigma_{yy}=\tau_{xy}=\tau_{yx}=0$
* -
* -
* -
### 3.2: Case: Pure shear
* For the pure shear case, $\sigma_{xx}=\sigma_{yy}=0$ and $\tau_{xy}=\tau_{yx}\not ={0}$.
* -
* -
* -
### 3.2: Case: Biaxial tension
* For a biaxial tension case, $\sigma_{xx}\not ={0}$, $\sigma_{yy}\not ={0}$ and $\tau_{xy}=\tau_{yx}=0$.
* -
* -
* -
## 4: Summary of Equations
* For uniaxial tension:
$$
\sigma_{\theta}=\displaystyle\frac{\sigma_{xx}}{2}+\displaystyle\frac{\sigma_{xx}}{2}\cos 2\theta
$$
$$
\tau_{\theta}=-\displaystyle\frac{\sigma_{xx}}{2}\sin 2\theta
$$
* General stress transformation equations:
$$
\tau_{\theta}=-\displaystyle\frac{\sigma_{xx}-\sigma_{yy}}{2}\sin 2\theta+\tau_{xy}\cos 2\theta
$$