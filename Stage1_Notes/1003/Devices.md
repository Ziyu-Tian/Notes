# Devices
## Part 1 Transformer
### 1.1 what is a transformer
* The transformer is a device that changes AC energy at one voltage level to another voltage level through the action of he magnetic fields.
### 1.2 What does a transformer do?
* Changing the voltage level
* Marching source and load impedances of maximum power transfer.
* Electrical isolation.
* Does not change the power and the frequency of the signal.
### 1.3 How the transformer works?
#### 1.3.1 The main principles
* Electromagnetism:
the current make the magnetism.
* Electromagnetic Induction:
the magnetism produce the electrical current.
#### 1.3.2 Principle of operation
* A changing magnetic field induces an emf.(By Faraday)
* $E=-\displaystyle\frac{d\varPhi B}{dt}$
* The AC input current produce the magnetic flux. Then the magnetic flux induces another AC voltage in the secondary winding.
### 1.4 Voltage and current ratios
#### 1.4.1 Voltage ratio
$$
\displaystyle\frac{V_1}{V_2}=\displaystyle\frac{N_1}{N_2}
$$
#### 1.4.2 Utilisation of magnetic core material and saturation
* $\varPhi=\displaystyle\frac{NI}{S}$, and $S$ is the reluctance.
* $V_1=N_1\displaystyle\frac{d\varPhi}{dt}=N_1\omega\varPhi_{max}\cos \omega t$
* $\varPhi_{max}=B_{max}A$
* $V_{1,rms}=N_1B_{max}A\omega/\sqrt{2}$
#### 1.4.3 Current ratio
* $\varPhi S=N_1I_1-N_2I_2$
* $S$ is usually small
* $N_1I_1\approx N_2I_2$
* $\displaystyle\frac{I_2}{I_1}=\displaystyle\frac{N_1}{N_2}$
#### 1.4.4 Equivalent circuits of an ideal transformer 
$$
V_2=\displaystyle\frac{N_2}{N_2}V_1
$$
$$
I_2=\displaystyle\frac{N_1}{N_2}I_1
$$
$$
V_2I_2=V_1I_1
$$
#### 1.4.5 Choice of the turns
* Choose turns to ensure core does not saturate.
* Higher voltage requires more turns.
* Higher $f$ requires more turns.
* Higher current requires thicker coil.
### 1.5 The equivalent circuit
#### 1.5.1 Practical transformer
* Real transformer
  * have losses
  * have leakage flux
  * have finite permeability of magnetic core.
* Real power losses
    * resistance in winding ($I^2R$)
    * core losses due to eddy current and hysteresis.
#### 1.5.2 Equivalent circuit of practical transformer
* The inductance and resistance can be expressed as a series of resistance and inductors.
* The magnetizing inductance can be expressed as a parallel of resistance and inductor.
* If we treat $a=\displaystyle\frac{N_1}{N_2}$, the load at the secondary side is $Z_L$
* The equivalent of $R,Z,X(Inductance)$:
  * $R_2^{\prime}=a^2R_2$ 
  * $X_2^\prime =a^2X_2$
  * $Z_L^\prime=a^2Z_L$
  * $I_2^\prime=\displaystyle\frac{I_2}{a}$
* This is called secondary current referred to primary.
* The circuit can be simplified by using $R_{e1}$ and $X_{e1}$ to simplify the total $R$ and $X$.
* $Z_{e1}$ is to express the sum of $R$ and $jX_{e1}$
* The referring to the secondary circuit is similar, which we should use the inverse of the $a$ to replace $a$.
   * $V_1^\prime=\displaystyle\frac{V_1}{a}$
### 1.6 The determination of transformer parameters
#### 1.6.1 Open circuit test (O.C.)
* Performed on L.V. side and keeping H.V. open circuited.
* The test is to determine the magnetic impedance value ,$R_0$, $X_0$
* Gradually increase the voltage till reach the rated voltage.
