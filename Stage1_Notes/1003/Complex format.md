# 7: Reactance and Impedance
## 7.1 The meaning of $j$
* Consider a sin signal $s(t)$ with a magnitude $S$ and phase displacement of $\displaystyle\frac{\pi}{4}$radians leading ,this may be written :$s(t)=\angle\displaystyle
\frac{\pi}{4}=\displaystyle\frac{S}{\sqrt{2}}(1+j)$
* Now consider multiply $s(t)$ by $j$ :
$j\times s(t)=S\angle \displaystyle\frac{3\pi}{4}$
* The $j$ means to transfer the vector by 90 degrees in anti-clockwise.(multiply)
## 7.2 Reactance of a inductor
* As we know:$v(t)=L(\displaystyle\frac{di}{dt}=\omega LI_{max}\cos\omega t)$
* The reactance of the inductor will now be defined as:$X_L=\omega L$
* So $v(t)=X_LI_{max}\cos\omega t$
* $V=jx_LI$
* The inductor current lags the voltage by 90 degrees.
## 7.3 Impedance of an inductor 
* Ohm's law can be directly compared to this phasor equation:
$Z_L=\displaystyle\frac{V_L}{I_L}=jx_L$
## 7.4 Reactance and impedance of a capacitor
* $i(t)=\omega CV_{Max}\cos\omega t$
* The reactance of the capacity is defined as :
$X_C=\displaystyle\frac{1}{\omega C}$
* $V=\displaystyle\frac{I}{j\omega C}=-jX_CI$
* The minus sign in that equation indicates that the capacitor current leads the voltage by 90 degrees.
* The impedance of the capacitor $Z_C$ is given by :$Z_C=-jX_C$
* For a resistor , the Z is equal to R, and Ohm's law could applied.
# 8: AC Circuit Analysis Techniques
## 8.1 Analysis techniques for complex impedance
* For a simple RLC circuit which is given by ($R+jX_L+jX_C$),$Z=R+j\omega L -j\displaystyle\frac{1}{\omega C}$
* Circuits with more than one source can the superposition theory.
# 9: AC power basic definition
* AC power analysis is complicated by the fact energy may be stored in electrical fields as well as the resistive loss.
* The energy $W(t)$:
$W=\int_{t_0}^{t_0+\delta t}$
* $P(t)=\displaystyle\frac{dw}{dt}=v(t)i(t)$
* A numerically positive $P$ indicated power flow from the supply to the load.
* A numerically negative $P$ indicated power flow into the supply from the load.
## 10: AC power in circuit elements
### 10.1 AC power absorbed by a resistor
* For a purely resistance load and a sin voltage is given:
$v(t)=V_{max}\sin\omega t$, while the current is:$i(t)=I_{max}\sin\omega t$
* $P(t)=V_{rms}I_{rms}=(I_{rms}^2)R$
* The instantaneous power absorbed by the resistance around the average value ($P$),but never goes negative.
### 10.2 AC power absorbed by an inductor
* If a sin current that$i(t)=I_{max}\sin \omega t$
* Then the voltage will be:
$v(t)=L(\displaystyle\frac{di}{dt})=\omega LI_{max}\cos \omega t$
* The inductor current lags the voltages by 90 degrees.
* $P(t)=v(t)i(t)=V_{rms}I_{rms}\sin 2\omega t$
* The power absorbed by the inductor load in one half cycle is returned to the supply during the next half cycle and no net power is delivered to the load.
### 10.3 AC power absorbed by a capacitor 
* If the sin current $i(t)=I_{max}\isin \omega t $ is given.
* $i(t)=C(\displaystyle\frac{dv}{dt})=\omega CV_{max}\cos\omega t$
* The capacitor voltage lags the voltage by 90 degrees.
* $P(t)=V_{rms}I_{rms}\sin 2\omega t$
* Same as the inductor.
## 11: Real and reactive power
### 11.1 Reactive power
* In purely capacitive or inductive loads the net power absorbed is zero.
* However, the source still needs to supply the pulsating power, $V_{rms}I_{rms}$
* The unit of it is $volt-amperes-reactive$, (VAr)
* Reactive power(Q),
$Q=V_{rms}I_{rms}$
   * Using the ohm's law:
   * $Q=X_L(I_{rms})^2$
   * $Q=X_C(I_{rms})^2$
* Real and reactive power in a general two-germinal network:
   * This time the load is not purely resistive,inductive or capacitive ,but a general load made up of a combination of all three circuit elements.Load voltage and current waveforms will be out of phase by an angle $\phi$($\theta$)
   * $v(t)=V_{max}\sin \omega t$ and $I_{max}\sin(\omega t-\phi)$
* The power $P(t)$ supplied to the load is given by : $P(t)=v(t)i(t)=(V_{max}\sin\omega t)(I_{max}\sin\omega t-\phi)$
* I.e: $P(t)=V_{rms}I_{rms}[\cos\phi -\cos(2\omega t-\phi)]$
* This can also be written as :
$P(t)=V_{rms}I_{rms}\cos\phi(1-cos2\omega t)-V_{rms}I_{rms}\sin\phi\sin 2\omega t$
(In this form, it may be seen that the power $P(t)$ is made up of two components, both pulsating at twice the supply frequency.
* The first component, given by $V_{rms}I_{rms}\cos\phi(1-\cos 2\omega\phi$ but never goes negative.
* The second components, given by $V_{rms}I_{rms}\sin\phi\sin 2\omega t$, has a peak value of $V_{rms}I_{rms}\sin\phi$ and a mean of zero.
### 11.2 Real power
* The real power $P$ is defined as the average value of $P(t)$ given by: $P=V_{rms}I_{rms}\cos\phi$ (Watts)
* This the useful power delivered to the load.
* The peak value of the second component that is forever travelling backward and forward between the load and the supply is the reactive power $Q$ given by $Q=V_{rms}I_{rms}\sin\phi$ (VArs)
### 11.3 Reactive power conventions
* Reactive power consumed in an inductor (i.e.when the current lags the voltage) is regarded as positive reactive power.
* Reactive power consumed in a capacitor (i.e.when the current leads the voltage) is therefore regarded as negative reactive power.
* The reactive power input to the two terminals is the algebraic sum of the reactive power of each branch of element.
* We must attach the appropriate sign to the reactive power of each element, positive for lagging reactive power(inductive load) and negative for leading reactive power(capacitive load).
### 11.4 Principle of conservation of power and reactive power
* In any linear two-terminal network with sin voltages and currents, the total power and the reactive power inputs to the two terminals is equal to the sum of the powers and reactive powers dissipated in each branch or elements within the network.
## 12: Complex power
### 12.1 Real and reactive components of the signals
* Consider the simple RL circuit shown below,where the I lags the V by an angle between 90 degrees and 0 degrees.
* -
* -
* -
* -
* The phasor diagram representation shows that the current may be resolved into two parts.The first components is in phase with the V phase and second with 90 degrees out of phase with the voltage.
### 12.2 Real and reactive components of signals
* The power equations for P and Q can therefore be re-written:
$P=VI\cos\phi=VI_P$
$Q=VI\sin\phi=VI_Q$
* Where $V$ and $I$ are rms values of voltage and current.$I_P$ is the rms value of the in-phase current components, and $I_Q$ is the rms values of the quadrature current components 90 degrees out of phase with the current.
* Power is given by he product of the voltage and the in-phase current component, while the reactive power is the product of voltage and the quadrature component of the current waveform.
* Complex power:
    * The voltage and current phasors the series RL circuit may be expressed in complex form as:$V=V\angle 0$, $I=I\angle -\phi$
    * The complex power, $S$ is defined by $S=VI^*$
    * where $I^*$ is the complex conjugate of $I$ given by,$I^*=I\angle \phi$
    * Thus, $S=VI^*\angle \phi=VI\cos\phi+j\sin\phi$
    * Combing the above equation with the equations for $P$ and $Q$ gives: $S=P+jQ$.
    * The real part of S is thus the real power $P$ and the imaginary part of $S$ is the reactive power $Q$.
    * The magnitude of $S$ is usually referred to as the apparent power with the unit of voltamperes(VA) and is given by:$S=VI=\sqrt{P^2+Q^2}$(VA)
## 13: Power factor & electrical power equations
### 13.1 Power Factor
* The power factor PF os an important parameter of ac electrical systems.
* It is defined as the ratio of the real power to the apparent power(VA) following through the system, ie.
$$
PF=\displaystyle\frac{Power}{Apparent Power}=\displaystyle\frac{VI\cos\phi}{VI}=\cos\phi
$$
* The term lagging and leading are always included when specifying the power factor.
* A lagging power factor means that the current lags the voltage and indicates the presence of an inductive load.
* A leading power factor means that the current leads the voltage and indicates the presence of a capacitive load.
### 13.2 Power factor and efficiency 
* Operation at a low power factor means that the required VA rating of the distribution plant is much higher than the average power it delivers.Most electrical circuits draw lagging VArs from the supply ,i.e.they will operate at a lagging power factor because of the presence of transformers.
* A common method of power factor correction is to place a capacitive load(usually a bank of capacitors) across the line. The capacitors will draw leading VArs thus reducing the total lagging reactive power drawn from the supply and bringing its power factor nearer unity.