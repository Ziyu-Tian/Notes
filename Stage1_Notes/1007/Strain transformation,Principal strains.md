# IV: Strain transformation, Principal strain and strain measurement
## 1: Plane Strain
* Same as the plane stress, $\varepsilon_{xx}$,$\varepsilon_{yy}$, $\gamma_{xy}$ may not ne non-zero, while other strain are zero.
## 2: Plane strain transformation equation
* For normal strain:
$$
\varepsilon_{\theta}=\displaystyle\frac{\varepsilon_{xx}+\varepsilon_{yy}}{2}+\displaystyle\frac{\varepsilon_{xx}-\varepsilon_{yy}}{2}\cos(2\theta)+\displaystyle\frac{\gamma_{xy}}{2}\sin(2\theta)
$$
* For shear strain:
$$
\displaystyle\frac{\gamma_{\theta}}{2}=-\displaystyle\frac{\varepsilon_{xx}-\varepsilon_{yy}}{2}\sin(2\theta)+\displaystyle\frac{\gamma_{xy}}{2}\cos(2\theta)
$$
* The angle $\theta$ is positive in the A/C direction from the horizontal.
## 3: Principal strain
### 3.1: The max and min strain
* $\varepsilon_1$ and $\varepsilon_2$ act in the same direction as the principal stresses.
* $\varepsilon_1$ is oriented 90 degrees from $\varepsilon_2$.
### 3.2: Th formula of the principal strain 
* The max and min of the principal strain can be find using the general formula.
* Direction of the strain:
$$
\theta=\displaystyle\frac{1}{2}\tan^{-1}\displaystyle\frac{\gamma_{xy}}{\varepsilon_{xx}-\varepsilon_{yy}}
$$
* The solution will be $\theta$ and $\theta +90$.
* The max of the shear strain can also be defined as:
$$
\gamma_{max}=\sqrt{(\varepsilon_{xx}-\varepsilon_{yy})^2+(\gamma_{xy})^2}
$$
or
$$
\gamma_{max}=\varepsilon_2-\varepsilon_2
$$
## 4: Strain measurement
### 4.1: Using strain measurement to get the stress and strain
* It is common to get the value of stress using the value of strain cause the stress is hard to measure.
* It is easy to calculate the value of $\varepsilon$ using the change of the resistance:
$$
R_0=\displaystyle\frac{\rho L}{A}
$$
while the change of the resistance can be expressed as:
$$
R_n=(\displaystyle\frac{L+\Delta L}{A-\Delta A})\rho
$$
And the volume of the metal is constant:
$$
V=L\times A=(L+\Delta L)(A-\Delta A)
$$
If we treat $\Delta R=R_n-R_0$:
$\Delta R\approx 2R_0\displaystyle\frac{\Delta L}{L}=2R_0\varepsilon$
* A more general form is :
$\Delta R\approx cR_0\varepsilon$ ,$c$ is a gauge factor that varied with the resistivity and Passion's ratio.(2 for metal and 10 fro carbon)
### 4.2: The way to detect the tiny change in strain
* In order to account for the tiny change in resistance due to the change of strain, we apply the **Wheatstone bridge** (a kind of electrical bridge):
$$
R_U=(\displaystyle\frac{R_2}{R_1}R_v)
$$ 
### 4.3: The Strain gauge rosettes
* The strain gauge rosettes is the multiple gauges which could measure the strain in different directions, which have 45,60 and 120 degrees in common.
* -
* -
* -
* For a 45 degrees gauge, $\varepsilon_{xx}=\varepsilon_A$, $\varepsilon_{yy}=\varepsilon_C$ and $\varepsilon_{45}=\varepsilon_B$, the $\tau_{xy}$ can also be got using these.