# XIII: Electrical Materials (Band theory and Doping)
## 1: Atomic structure
* The electron suffer from both the force from nucleus and other electrons.The solution to this quantum mechanical problem of an atom is he Band theory(electrons in different orbital path by their different energy)
    * -
    * -
    * -
    * -
* The electron is a fermion so that obey the Pauli exclusion principle and have an intrinsic spin(up or down).
    * -
    * -
    * -
    * -
* States are occupied in he increasing energy until the max number of the electrons.
* The elements in the same column have similar electrons format in the highest energy state, i.e.valence states.(Mainly control the chemistry properties)
## 2: Electronic structure for solids
* As for Na, more and more Na atoms leads to the formation of quasi-continuous bands.
    * -
    * -
    * -
* Bands are filled according to the increased energy.The nature of the highest energy occupied level determines whether the it is a metal or non-metal:if it is within a band, it is a metal; if it is at the top of the band, then it is a non-metal.
* The range of energy between the occupied (valence bands) and empty bands (conduction bands) is called the bandgap.
    * -
    * -
    * -
    * -
## 3: Temperature effects
* As T increases in a solid material, several things happens:
    * Atoms vibrate about the equilibrium position
    * Things(atoms,ions,vacancies) may diffuse.
    * Electrons may be excited into a empty state due to collision.
    * The solid may melt or sublime
* The thermal energy at an absolute temperature of T is given by: $E=k_BT$, where $k_B$ is Boltzmann's constant. 
* Increasing T increases the probability an electron is excited into a higher,empty energy level. The probability for a valence electron being excited to conduction band is proportional to the exponential term: $e^{-E_g/2k_BT}$.
* Exciting an electron to a conduction band leaves behind a hole, which acts as a positively charged electron.
    * -
    * -
    * -
    * -
## 4: Charge neutrality
* The excitation of an electron does not change the number of electrons in the system.We need to keep track of the number of the electrons are in conduction band and in the valence band, for which we have **notation**.
    * -
    * -
    * -
    * -
* In an **uncharged** material, the density of conduction electrons ($n$) and valence holes($p$) **is equal** : $n=p$. For pure materials these carriers are **intrinsic**, and indicates with the subscript $i$ : $n_i=p_i$. And $n_i$ varies with $E_g$ and $T$. If $E_g$ is larger, the $n_i$ will be larger.
## 5: Electrical conduction and band-structure 
* When an E-field is applied to a material, electrons experience a force: $F=-eE$. **Free electrons** accelerate , gaining $E_k$. This movement is the $I$. Conventional current follows the motion of electrons. For electrons to direction of electrons. For electrons to move, they need somewhere to go, which is a **quantum mechanical property**.
### 5.1 Metals: $E_g$=0eV
* If $E_g$=0eV there are empty states **immediately** above the highest energy states.Electrons close in energy to empty states excited into them. In practice, **only a few % electrons in a metal being those close to empty states, contributes to conduction**.
#### 5.1.1 Calculation of the concentration of conduction electrons in Na
* Calculating the number density of conduction electrons in Na metal assuming 3% of electrons are able to contribute.
* The data of Na:
    * -
    * -
    * -
* **Solution:**
    * The number of Na atoms per $m^3$ is: $\displaystyle\frac{968}{23\times1.67\times10^{-27}}$
    * Each atom have 11 electrons, the total number of electrons is: $11\times\displaystyle\frac{968}{23\times1.67\times10^{-27}}$
  * If 3% are involved in conduction, the concentration which can conduct the electricity is: $0.03\times11\times\displaystyle\frac{968}{23\times 1.67\times 10^{-27}}$
### 5.2 Semiconductor:$E_g$ is small
* In E-field, electrons and holes accelerate in **opposite directions**.Intrinsic semiconductors (Si) have just a few charge carriers. The current is proportional to the **carrier concentration**, so Si is not a good conductor in 300K.The total current is the sum of the electrons current( in the conduction band) and hole current(missing electrons in the valence band).
* -
* -
* -
* The electron and hole current **add** because a flow of positive charge in one direction **is equivalent to the flow of negative charge in the opposite direction.
### 5.3 Insulators:$E_g$ is large
* In **Electrically insulating** materials, exactly the same thing happens as in semiconductors.
* However, the large bandgap means that at any given T, $n_i$ is much smaller than in the semiconductors
## 6:Chemical modification of materials for electrical conduction:doping
* There are intrinsic carriers in semiconductors at 300K.
* Adding impurities can increase the conductivity, which termed **doping**.
* Adding **dopants** resulted in **extrinsic** semiconductors.
* Insulating materials are mede conductive by doping.
* There are limitations and guiding principles for the choice of thee dopants.
### 6.1 N-type doping: increasing the density of the conduction electrons
* The element P have one more valence electron than Si. Replace the Si with P in a crystal can lead to the excess of electrons.The P dopant becomes a positive ion, whose Coulomb field weakly binds a **negative charged electrons**. At 300K the attraction is too weak to hold the electrons: **the depant is ionised, and the fifth valence electron is released to the conduction band.**
* This doped,extrinsic semiconductors is labelled as **n-type** because we adding the **negative charge**, and the dopant is termed a donor.
* The conduction electron density in this case is $n_n$=[P], where [X] signifies the concentration of X (numbers per volume), and the concentration of donor is given $N_D$.
* The donated electrons **add** to the **intrinsic** concentration  $n_i$, but in practical doping $N_D>>n_i$, it is approximately $n_n=N_D$
* Some donor electrons cancel the intrinsic holes in the valence band, $p_i$. This recombination reduced the hole concentration , so $p_n<p_i$.
### 6.2 Relationship between $n,p,n_i$ and $p_i$
**Exactly** what is happening to the number of electrons and holes involved in electrical conduction is captured in the relationship: $np$ =constant, this is **independent of doping**, so we can use:$np=n_ip_i$ (=constant)
* In **Intrinsic material** the concentration of conduction electrons must equal the concentration of valence holes(neutral), $n_i=p_i$, so $np=n_i^2$
* This allow the calculation of the hole concentration in n-type material:
$$
np=n_i^2\rightarrow p=\displaystyle\frac{n_i^2}{n}\approx \displaystyle\frac{n_i^2}{N_D}
$$
### 6.3 P-type doping : increasing the density of valence band holes
* -
* -
* -
* To increase the number of holes, dopants with fewer electrons than the host are added (These dopants are called acceptors because they accept the electrons and leaving holes ). For silicon, boron(B) has one fewer than Si and become negative with a positively charged hole trapped in the E-field.
* The acceptor concentration is denoted $N_A$, and 300K in Si these are virtually all ionised: $p_p\approx N_A$
* $n_pp_p=n_i^2\rightarrow n_p=\displaystyle\frac{n_i^2}{p_p}\approx \displaystyle\frac{n_i^2}{N_A}$
## 7:Carrier compensation:combing electrons and holes
* For a given voltage(E-field),the current is proportional to the concentration of charge carriers, the total current in semiconductors being the sum a hole and an electron current.If we could increase the $n$ and $p$ in the same time, then the conductivity would be significantly enhanced. Thus it might seem a good idea to **doping with both donors and acceptors** .
* -
* -
* -
* However it failed, acceptors and donors exchange charge directly. The electron or hole concentration obtained is difference in the donor and acceptor concentration, not the sum.
* If $N_A>N_D$, the material is p-type with $p=N_A-N_D$, whereas vice versa. Additionally, the mobilities reduced and the conductivity reduced. But this method have some usages in engineering fabrication.