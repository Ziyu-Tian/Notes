# III: Principal stresses and Failure Criteria
## 1: Principal Stresses
### 1.1: The Principal stresses: Max and Min
* The principal stresses $\sigma_1$ and $\sigma_2$ acts on the principal planes, which the **shear stress** is zero.
* They are orthogonal, $\sigma_1$ is oriented 90 degrees from $\sigma_2$.
* The third principal stress acts in the out-of-plane direction which is zero in **2D**.
* Usually,$\sigma_1$ is algebraically the max normal stress while $\sigma_2$ is the least.
* However the $\sigma_2$ maybe have large magnitudes when it is compressive (negative).
* Principal planes are mutually inclined at 90 degrees.
### 1.2: The formula of the max and min
* $\sigma_1=(\displaystyle\frac{\sigma_{xx}+\sigma_{yy}}{2})+\sqrt{(\displaystyle\frac{\sigma_{xx}-\sigma_{yy}}{2})^2+\tau_{xy}^2}$
* $\sigma_2=(\displaystyle\frac{\sigma_{xx}+\sigma_{yy}}{2})-\sqrt{(\displaystyle\frac{\sigma_{xx}-\sigma_{yy}}{2})^2+\tau_{xy}^2}$
* The direction $\theta$ can be defined as: $\theta=\displaystyle\frac{1}{2}\tan^{-1}\displaystyle\frac{2\tau_{xy}}{\sigma_{xx}-\sigma_{yy}}$
## 2: The third principal stress
* In 3-D situation, there is a $\sigma_3$ which is perpendicular to the $\sigma_1$ and $\sigma_2$.
* In 2-D the $\sigma_3$=0.

## 3: Maximum shear stress
* $\tau_{max}=\sqrt{(\displaystyle\frac{\sigma_{xx}-\sigma_{yy}}{2})^2+\tau_{xy}^2}$
* When the maximum shear stress applied, thw normal stress can be defined as $\sigma_s=\displaystyle\frac{\sigma_{xx}+\sigma_{yy}}{2}$.
* The direction of the shear stress can be expressed as: (from the horizontal)
$$
\theta=\displaystyle\frac{1}{2}\tan^{-1}(-(\displaystyle\frac{\sigma_{xx}-\sigma_{yy}}{2\tau_{xy}}))
$$
* And the positive sign show the A/C while negative sign show the CW.
## 4: Relationship between principal stress and max shear stress
* $\tau_{max}=\displaystyle\frac{\sigma_1-\sigma_2}{2}$
* The degree between the principal stress plane and max shear stress plane is 45 degrees.
## 5: The Failure Criteria
### 5.1: Introduction
* **Yield criteria** for ductile material (some of the metal) and **Fracture criteria** for brittle material (stone and ceramic ) and for other failure material like buckling it need other criteria.
### 5.2: Failure criteria for ductile material (yield)
#### 5.2.1: **Tresca criterion**
* Also known as the max shear stress criterion.
* $\tau_{max}=\displaystyle\frac{\sigma_Y}{2}$
* For $\sigma_1$ and $\sigma_2$ have different sign, taking $\sigma_1>\sigma_2$:
$$
\tau_{max}=\displaystyle\frac{\sigma_1-\sigma_2}{2}
$$
* For $\sigma_1$ and $\sigma_2$ have same sign, taking $\sigma_1>\sigma_2$:
$$
\tau_{max}=\displaystyle\frac{\sigma_1-\sigma_3}{2}=\displaystyle\frac{\sigma_1}{2}
$$
* For **Tresca criterion**, we use the most severly stressed point to find the **factor of safety**:
$$
n=\displaystyle\frac{\sigma_Y/2}{\tau_{max}}
$$
#### 5.2.2: **Von Mises Criterion
* Also known as distortion strain energy criterion。
* The Von Mises stress can be expressed as:
$$
\sqrt{\displaystyle\frac{1}{2}[(\sigma_1-\sigma_2)^2+(\sigma_2-\sigma_3)^2+(\sigma_3-\sigma_1)^2]}=\sigma_Y
$$
* And the factor of safety can be expressed as $\sigma_Y$/von mises stress
## 6: Failure criteria for brittle materials (fracture)
* According to the Rankine criterion, the fracture occurs when: $\sigma_{max}=\sigma_{ult}$, where the $\sigma_{max}=max(|\sigma_1|,|\sigma_2|,|\sigma_3|)$.
* In this criterion:
$$
n=\displaystyle\frac{\sigma_{ult}}{\sigma_{max}}
$$
