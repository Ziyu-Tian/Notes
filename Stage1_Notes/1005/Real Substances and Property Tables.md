### 4.6: Thermal Equations of the mixed gases
* If there are two components of gases named $A$ and $B$, while their T is $T_A$ and $T_B$ repetitively.
* After they have been mixed their final temperature is $T_2$.
$$
m_Ac_A(T_A-T_2)=m_Bc_B(T_2-T_B)
$$
# XIII: Real Substances and Property Tables
## 1: Introduction
## 1.1: Real Substances
* Not all the substances behave like ideal gases.
* Cannot use ideal gas law
* **Solution**: looking things up in the **Property table.**
    * Moran and Shapiro
## 1.2: Notation
* Lower letter usually denotes a specific quantity.
* Tile $\widetilde{.}$ is a molar quantity.
* Examples:
    * $u$ is specific internal energy.
    * $h$ is specific enthalphy, $h=u+pv$, which has unit of kJ/kg.
* Subscript:
    * $s$ means saturated.
    * $f$ means saturated liquid.
    * $g$ is saturated vapour.
    * $fg$ denotes change of phase at constant pressure.
    * $h_{fg}=h_g-h_f$
## 2: Linear interpolation
### 2.1: Example_1
* No entry to find the specific latent heat of vaporisation at 63 degrees from the table.
* There are values at 60 and 65.
* So we interpolate at 60 and 65.
* $\alpha=\displaystyle\frac{63-60}{65-60}=0.6$
* Solution:
$$
h_{fg}[63]=h_{fg}[60]+\alpha (h_{fg}[65]-h_{fg}[60])=2351.1 kJ/kg
$$
### 2.2: Dryness Fraction
* A saturated mixture is made up of part of vapour and part of liquid.
* We quantify just how much using the dryness fraction $x$.
* $x$ only defined when saturated.
* $x=1$ means dry- saturated vapour.
* $x=0$ means wet-saturated liquid.
* Specific Enthalpy:
$$
h(x)=h_f+x(h_g-h_f)
$$
* Specific volume:
$$
v(x)=v_f+x(v_g-v_f)
$$
## 3: The classification of steam (gases)
### 3.1: Unsaturated steam
* During the vaporization continuing, if the mount of the water molecules **flying into the air** is less than that **enter the water from the air**, we call it **unsaturated steam**, cause the vaporization still can processing.
### 3.2: Saturated steam
* When the water molecules flying into the air equal to that enter the water, i.e reach a balance, we call it **saturated steam** cause the vaporization stopped.
### 3.3: Superheated steam
* When the water have already reach the saturated steam but we still increase the temperature, so the T has over the **saturation temperature** at this pressure, it will be **Superheated steam** as a kind of **unsaturated steam** so we have to use another table to do the linear interpolation.
