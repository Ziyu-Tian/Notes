# II: Electro-magnetism
## 1: Inductance
### 1.1 Definition of capacitance
* The electrostatic potential:$\Delta\phi =V=|\vec{E}|w$
* The capacitance is:$C=\displaystyle\frac{\varepsilon A}{w}=\displaystyle\frac{Q}{V}$
* w( or d) is for wide and A (or S)is for area above.
* Definition of inductance
    * Self-inductance of a circuit : $\phi=Li$
    * For multiple turns: $\Psi=N\phi$, and $\Psi=Li$
* The unit is Wb/A or Henry,H.
### 1.2 Voltage and inductance
  * Inductance definition: $\Psi=Li$
  * Faraday law:$|V|=\displaystyle\frac{d\Phi}{dt}$
  * Product rules: $|V|=\displaystyle\frac{dL}{dt}i+L\displaystyle\frac{di}{dt}$
  * Add the resistance:$|V|=L\displaystyle\frac{di}{dt}+iR$
  * So the power: $P=i|V|=iL\displaystyle\frac{di}{dt}+i^2r$
  * Energy in the field: $U_{ind}=\int^{t_{1}}_{t_{1}}U(t)dt$, i.e:$U_{ind}=\displaystyle\frac{Li_2^2}{2}-\displaystyle\frac{Li_1^2}{2}$
### 1.3:Inductive coupling: a two coils system
* The metal ring produce a path for the magnetic flux.
* One side is wrapped with coils and a power supply while the other side only has the coils.
* The changing flux in the first coils interact the second side: This is the Faraday's Law apply.
* Th flux in the first coils: $\Psi_1=N_1\phi_1=i_1L_1$
* The flux in the second coils: $\Psi_2=N_2\phi_1=\displaystyle\frac{N_2}{N_1}L_1i_1=M_{21}i_1$
* The quantity $M_{21}$ is called mutual inductance.
* $M_{21}=M_{12}$
### 1.4: Inductive coupling : Energy
* $L_1$ is the self-inductance of coil 1, is a measure of how hard to change the current. i.e:  $U=\displaystyle\frac{L_1i_1^2}{2}$, and $U$ for energy.
* Now $\phi_2$ through coil 1 comes from coil 2: $\Psi_1=i_1L_1+M_{12}i_2$
* $U=\displaystyle\frac{L_1i_1^2}{2}+M_{12}i_1i_2+\displaystyle\frac{L_2i_2^2}{2}$
## 2: Circuits equivalence
### 2.1 Magnetomotive force and the reluctance
* The amount of source of flux(MMF)
* MMF is equivalent to the battery(emf).
* The resistance to the flux is called the reluctance.
### 2.2 The analogy to the Ohm's Law
* emf $\rightarrow$ MMF
* $i \rightarrow \phi$
* emf=V=IR $\rightarrow$ MMF= F =$\phi S$
* $R=\displaystyle\frac{l}{\sigma A}$, $S=\displaystyle\frac{l}{\mu A}$
* Materials dependance: $\sigma$ and $\mu$
* $S=\displaystyle\frac{N^2}{l}$
* S for reluctance.
### 2.3 Combining reluctance
* Same as the resistance.
## 3: The Lorentz Force
* $\vec{F}=q\vec{E}+q\vec{u}\times \vec{B}$
* The second part is non-zero only if the charge $q$ is moving in $\vec{B}$ and not in the same direction as $\vec{B}$.
* Use the right hand rule can find the direction of the second part.
* Fore on a moving charge in a uniform magnetic field
    * $\vec{B}=\mu \vec{H}$
    * A electron moving through it at right angles.
    * As it enter the field it experiences the Lorentz force $\vec{F}=q\vec{u}\times\vec{B}$
    * It is circle motion.
* Force on a current in a uniform magnetic fields:
    * $\vec{F}=i\vec{l}\times\vec{B}$
    * For the current and the field at the right angles:$F=Bil$ or $F=Bil\sin\theta$
* Force between two currents:
    * Approximate as vacuum.
    * Current 1 gives a circulating magnetic field.
    * Magnitude of field at wire 2 can be found by Biot-Savart: $\vec{B_1}=\displaystyle\frac{\mu_0i_1}{2\pi d}$
## 4: Motional emf
### 4.1 Motional induced emf
* $\vec{B}=\mu \vec{H}$
* $\vec{F}=q\vec{u}\times B$
* Which generate the $\vec{E}$ from separated charges and an opposite force.
* $E=uB$.
* $V=BLu$.(same as $BLv$)
* u is same as v.
## 5: Force from the energy
### 5.1 Force from the filed energy
* For permanent magnets, there is not current so that we can't use the Lorentz's law.
* Energy stored in a magnets : $Energy=V\displaystyle\int_V\vec{H}\vec{B}=\displaystyle\frac{B^2}{2\mu_0}V$
* The force is a change that reduce the energy.
* $F=-\displaystyle\frac{B^2A}{2\mu_0}$, which is independence of distant.
* It is not valid for constant current.