# VIII:Fluid Flows
## 1: Real and Ideal Fluids
* The most commonly used simplification is called an ideal fluid.
* An ideal fluid is incompressible(the constant $\rho$), non-viscous(negligible $\mu$), and has no surface tension.
* The real fluid with viscous in the real situation are called real fluid.
## 2: Newtonian and Non-Newtonian Fluids
* For solid, there is a linear relationship between the shear stress $\tau$ and shear strain
$\gamma$.
* For liquid,the same relationship exists in the shear stress and shear strain(=velocity gradient),with the constant of dynamic viscosity $\mu$.
* Newton's law of viscosity: $\tau=\mu\displaystyle\frac{du}{dy}$
* Fluids obey Newton's law of viscosity are known as Newtonian Fluids.
* -
* -
* -
## 3: No-slip Condition and Boundary Layer
* A fluid flowing over a stationary surface comes to a complete stop at the surface cause no-slip conditions.
* -
* -
* -
* -
* Boundary Layer: The flow region adjacent to the wall in which the viscous effects (velocity gradient) are significant.
* -
* -
* -
## 4: Streamlines, Streamtubes, Pathlines, and Streaklines
* **Streamline:** A curve that everyone tangent to the local vector.
    * Streamlines as indicators of the **instantaneous direction of fluid motion** throughout the flow field.
    * -
    * -
    * -
    * Streamlines cannot be directly observed experimentally,except in steady flow fields.
* **Streamtube:** consist a bundle of streamlines like a communications cable consist of some fibre-optic cables.
    * Since streamlines are everywhere parallel to the local velocity, fluid cannot cross the streamline.
    * Fluid within the streamtube cannot cross the boundary of the tube.
    * -
    * -
    * -
    * Both streamlines and streamtube are instantaneous quantities, defined at a particular instant in time according to the velocity field at that instant.
* **Pathline:** The actual path traveled by an individual fluid particle over some time period.
    * Lagrangian concept- we simply follow the path of an individual fluid particle as it moves around the flow field.
    * -
    * -
    * -
* **Streakline:** The locus of fluid particles that have passed sequentially through a prescribed point in the flow.
    * Streakline are the most common flow pattern generated in a physical experiment.
    * If you insert a small tube into a flow and introduce a continuous stream of tracer fluid, the observed pattern is a streakline.
    * -
    * -
    * -
* **Streakline,streamline and pathline are identical in  steady flow but cna be different in unsteady flow.
## 5: Classification of Fluid Flows
* Confinement:internal and external flow
* Dimensionality: 1 or 2 and 3-D flows
* Steadiness: steady or unsteady
* Uniformity: uniform and non-uniform
* Rotationality: rotational and irrotational
* Laminarity: laminar and turbulent
* Spatial regions: viscous and non-viscous
## 6: Internal and external flows
* Depending on whether the fluid is forced to flow in a confined channel or over a surface.
    * External flow: Unbounded fluid
    * Internal flow: Completely bounded by solid surface.
    * The flow of fluid in a duct is called **open channel flow** if the solid bound is partially filled(like river).
* Internal flows are dominated by the influence of the viscosity throughout the flow field, while in external field the viscous effect only limited to the boundary layers near solid surface.
## 7: 1,2 and 3-D Flows
* A flow field is beat characterized by its velocity distribution.
* **A flow is said to be 1,2 or 3-D if the flow velocity varies in 1,2 or 3-D ,respectively.**
* The variation of velocity in certain direction can be ignored in other directions.
* -
* -
* -
## 8: Steady versus Unsteady Flow
* **Steady** means no change at a point with time
* The steady flow assumption regards flow parameters such as velocity, pressure and density as time independent.
* For steady flows, $\displaystyle\frac{\partial u}{\partial t}=0$
* Many engineering devices operating for long time under the same conditions, and they are classified as **steady flow devices**.
* -
* -
* -
## 9: Uniform versus Non-uniform flow
* Uniform means no change with location over a specified region.
* A flow is constant if its characteristics do not vary between different of the domain at any constant.
* Flow in a pipe with a uniform cross-section is usually uniform.
* Flow with free surface is uniform only in special situation where the cross-section and there is a complete balance of forces. Mostly it is non-uniform in free surface situations.
## 10: Rotational versus Irrotational Flow
* The flow is termed rotational or vortex flow if the particles within the flow have rotation about any axis.
* The rotation is measured as an average angular velocity of small linear elements perpendicular to the given axis.
* -
* -
* -
* Irrotational or potential flow is flow without rotation.
    * Groundwater flow in porous media is usually considered to be irrotational.
    * Pipe and free-surface flows are usually rotational.
## 11: Laminar versus Turbulent Flow
* **Laminar flow**: The highly ordered fluid motion characterized by smooth layers of fluid. The flow of high-viscosity fluids such as oil at low velocities is typically laminar.
  * -
  * -
  * -
* **Turbulent flow:** The highly disordered fluid motion that typically occurs at high velocities and is characterized by velocity fluctuations. The flow of low-viscosity and high velocities is typically turbulent.
    * -
    * -
    * -
* **Transitional flow:** A flow that alternates between being laminar and turbulent.
    * -
    * -
    * -
* -
* -
* -
## 11: Laminar Flow
* Laminar flow or streamline flow occurs when a fluid in parallel layers with no disruption between the layers.
    * There are no cross-currents perpendicular to the direction of flow , no eddy or swills of fluid.
    * -
    * -
    * -
* Reynold number (Re)
    * The ratio of the inertial force to the shearing force of the the fluid.(=$\rho cD/\mu$)
    * How fast the fluid is moving relative to how viscous it is.
    * Velocity at a point is independent of time and no velocity fluctuation.
    * No component of velocity normal to mean flow direction.
        * -
        * -
        * -
## 12: Turbulent Flow
* Turbulence or turbulent flow is any pattern of fluid motion characterized by chaotic changes in pressure and flow velocity.
    * -
    * -
    * -
* Secondary, random velocity fluctuations superimposed on mean velocity. Much mixing, hence momentum interchange leads to more uniform velocity profiles.
    * -
    * -
    * -
## 13: Viscous versus Inviscid Region of Flow (Inviscid means no-viscous)
* **Viscous flow:** Flows in which the friction effects are significant.
* **Inviscid or non-viscous flow**: Flow of an inviscid fluid (viscosity is equal to 0) with no energy loss.
* **Inviscid flow regions**: In many flows of practical interest, there are regions(typically regions not close to solid surfaces) where viscous forces are negligibly small compared to inertial or pressure forces.
* -
* -
* -
## 14: Continuity Equations
### 14.1 Conservation Equations of Fluid Flow
* Conservation laws:
    * Conservation of mass
    * Conservation of Energy
    * Conservation of Momentum
* These are called **The Fundamental Equations**.
### 14.2 The Fundamental Equations
* Conservation of Mass:
    * For steady flow of an incompressible fluid: $Q=\int_A udA$, $Q=constant$ and $u$ is velocity of fluid.
    * For compressible fluid: $\dot{m}$=constant (kg/s)
* Conservation of Energy:
    * $\displaystyle\frac{p}{\rho g}+z+\displaystyle\frac{u^2}{2g}$=constant, The Bernoulli Equation.
* Conservation of Momentum
    * $\sigma \vec{F}=\dot{m}(\vec{u_2}-\vec{u_1}$
### 14.3 Control Volume
* A control volume is a fixed region in space bounded by a control surface or boundary.
    * -
    * -
    * -
* This boundary is positioned so that flow across it occurs only at locations where flow conditions are uniform.
* The size and the shape of a control volume are entirely **arbitrary** but frequently they are made to coincide with solid with solid boundaries.
    * -
    * -
    * -
### 14.4 Conservation of Mass
* Consider a control volume of fluid of density,$\rho$
* Mass of fluid within the control volume = $\int_{CV}\rho dV$
* If the fluid is flowing then the mass of fluid within the control volume may be changing.
* -
* -
* -
* Let's consider the rate of increase of mass within the control volume:
    * Rate of increase mass =$\displaystyle\frac{\partial }{\partial t}\int_{CV} \rho dV$
* Now consider the net rate of mass inflow to the control volume through the control surface.
* Let CS denotes the control surface and let $\vec{v}$ be the velocity perpendicular to the control surface.
* Rate of mass inflow = -$\int_{CS} \rho \vec{v}dA$
* Matter is conserved, so:
    * $\displaystyle\frac{\partial }{\partial t}\int_{CV}\rho dV= -\int_{CS}\rho\vec{v}dA$
* The rate of the increase of mass within a control volume is equal to the net rate of mass flow to the same control volume through the control surface, which is the **continuity equation** for unsteady flow.
    * $\displaystyle\frac{\partial }{\partial t}\int_{CV}\rho dV+\int_{CS}\rho\vec{v}dA$=0
* For steady flow, $\displaystyle\frac{\partial }{\partial t}\int_{CV}\rho dV$=0, so $\int_{CS}\rho\vec{v}dA=0$
* For incompressible fluid ($\rho$=constant), the equation can be reduced to: $\int_{CS}\vec{v}dA=0$
    * Let us consider a portion of pipe as an example:
    * -
    * -
    * -
    * $\int_{A_1}u_1dA_1=\int_{A_2}u_2dA_2$
* The average velocity for a cross-section is given by $\vec{u}\displaystyle\frac{1}{A}\int_A udA$:
* As $Q=\int_A udA$ and $\int_{A_1}u_1dA_1=\int_{A_2}u_2dA_2$, we can find $Q=\bar{u_1}A_1=\bar{u_2}A_2$.
* **Discharge** is a very important concept in fluid mechanics:
$$
Q=\bar{u}A
$$
* Therefore for steady incompressible flow ($\rho$ is constant), $Q=$constant.
## 14.5 Continuity Equation for Unsteady,Compressible Flow
* -
* -
* -
* -
## 14.6 Continuity Equation for steady flow at a pipe junction
* For a CV with multiple inlets and outlets
    * The algebraic sum of ghe mass flow rates at any pipe junction is **zero**.
    * -
    * -
    * -
* If the flow is incompressible($\rho _1=\rho_2=\rho_n$) or ($\rho=constant $):
    * -
    * -
    * -
* -
* -
* -
## 14.7 Discharge per Unit Width
$$
q=\displaystyle\frac{Q}{b}=\displaystyle\frac{uA}{b}=\displaystyle\frac{uhb}{b}=uh
$$