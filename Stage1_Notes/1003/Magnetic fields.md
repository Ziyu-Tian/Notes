# I Magnetism
## 1: Introduction
### 1.1 Gauss's Law of Magnetism
* The law related to the passage of the magnetic flux through a closed surface.
* No point source of M-fields.
* Flux must be circulate.
* For a fixed surface, the flux out is equal to that in.
* The M-pole cannot be enclosed.
### 1.2 The order of the magnitude for magnetic flux density, $\vec{B}$, in Tesla
* Surface of earth: $10^{-4}$
* Interstellar space:$10^{-8}$
* Iron magnet: $10^{-2}$
* Strong magnet: 1
* Superconducting solenoid:$1^{1}$ 
* Neutron:$10^{8}$
## 2: Magnetic fields
### 2.1: Empirical observations:Force in wires
* The same direction I affect each other.
* The different direction I reject each other.
### 2.2: Caparison with the electrical fields
* In electrical fields, $\vec{D}=\epsilon\vec{E}$,while the $\vec{D}$ is material independent.
* In magnetic fields,$\vec{H}=\displaystyle\frac{1}{\mu}\vec{B}$, while $\vec{H}$ is materials independent.
### 2.3: Gauss's Laws
* In E-fields,$\int_S \vec{D}.d\vec{A}=Q_{enclosed}$, and $\nabla.\vec{D}=\rho$
* In magnetic,
$\int_S.d\vec{A}=0$, and $\nabla.\vec{B}=0$
### 2.4: The Biot-Savart Law
* Biot-Savart Law -analogous to the principle of superposition 
* $\vec{H}=\int \displaystyle\frac{id\vec{l}\c\times\vec{r}}{4\pi r^3}$
* An example:
 a is the distance from a point to the wire with a current. The Biot-Savart shows that:$|\vec{H}|=\displaystyle\frac{i}{2\pi a}$,
 And $|\vec{B}|=\displaystyle\frac{\mu_r \mu_0i}{2\pi a}$
* Direction of the magnetic fields can be defined by the right hand screw rule.
* The geometric interpretation:
$i$ can be treated as the current passing the loop, and the $2\pi r$ is the length of the loop.
### 2.5: Ampere's Law
* $\oint_C \vec{H}.d\vec{l}=i$
* Just as the geometry interpretation above.
* The comparison of Gauss's Law and Ampere's Laws:
    * Gauss's Law:$\oint_S\vec{D}.d\vec{A}=q$
    * Ampere's Law: $\oint_C\vec{H}.d\vec{l}=i$
### 2.6: Magnetic field from a current loop
* The field at the centre is :
$\int\displaystyle\frac{id\vec{l}\times\vec{r}}{4\pi r^3}$
* r is the constant, and $d\vec{l}\times\vec{r}=rdl\hat{z}$
* $|\vec{H}|=\displaystyle\frac{i}{2r}$
### 2.7: An important application of Ampere's Law 
* N is the total length of the turn of the solenoid, n is the turns density.
* $\oint_C\vec{H}.d\vec{l}=\int_{B}^C \vec{H}.d\vec{l}=HL_{AB}=N_{AB}i$
* $H=\displaystyle\frac{N_{AB}}{L_{AB}}i=ni$
### 2.7: Faraday's Law
#### 2.7.1 Faraday's idea
* $i\rightarrow H$
* Faraday surmised $H\rightarrow i$
* What we need is to change the magnetic fields
#### 2.7.2 Induced e.m.f(voltage)
* The e.m.f is electromotive force.
* $\epsilon=-\displaystyle\frac{d\varPhi}{dt}$, where the $\varphi$ is the flux passing the loop.
* The sign of the voltage can be inferred by Lenz's Law.
* For coils, 
$$
\epsilon=-N\displaystyle\frac{d\varPhi}{dt}=-\displaystyle\frac{d\varPhi}{dt}
$$
#### 2.7.3 Application of Faraday 's Law 
* Voltage and induction
   * As we know above:$\varPhi=Li$
   * Apply Faraday's Law:$|V|=\displaystyle\frac{d\varPhi}{dt}$
   * i.e:$|V|=\displaystyle\frac{dL}{dt}i+\displaystyle\frac{di}{dt}L$
   * L is a constant in time so $\displaystyle\frac{dL}{dt}=0$
   * $|V|=L\displaystyle\frac{di}{dt}$
   * Add the resistance:$|V|=L\displaystyle\frac{di}{dt}+iR$
   * Now for the power:$P=i|V|=iL\displaystyle\frac{di}{dt}+i^2R$
* Energy in the field
    * $U_{ind}=\int_{t1}^{t2}P(t)dt$, i.e. $U_{ind}=\displaystyle\frac{1}{2}Li_{2}^2-\displaystyle\frac{1}{2}Li_{1}^2$
    * For an alternating current, the stored energy alternated.
*  Inductive coupling: a two coil system
    * A ring of metal forms a path for magnetic flux.
    * A coil of wire is wrapped around the ring.
    * The coil-1 is connected to a power supply while the coil-2 is not.
    * The changing flux from the first coil passes and interacts with the second coil,which generate the voltage.
    * The flux from coil-1 is:$\varPhi=N_1\varPhi_1=i_1L_1$
    * The flux passes through the coil-2:$\varPhi_2=N_2\varPhi_1=\displaystyle\frac{N_2}{N_1}L_1i_1=M_{21}i_1$
    * The quantity M_{21} is the mutual induction.
    * $U=\displaystyle\frac{1}{2}L_1i_1^2$
    * $\varPhi_1=i_1L_1+M_{12}i_2$
    * The total energy is :$U=\displaystyle\frac{1}{2}L_1i_1^2+M_{12}i_1i_2+\displaystyle\frac{1}{2}L_2i_2^2$
* Coupled coils and voltage
    * The alternating voltage in coil-1 generate a flux $\varphi_1$
    * Then in coil-2:
$$
|V_2|=\displaystyle\frac{d\varPhi _2}{dt}=\displaystyle\frac{N_2}{N_1}V_1
$$
