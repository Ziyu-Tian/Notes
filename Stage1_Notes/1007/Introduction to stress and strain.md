# I:Introduction to stress and strain
## 1:Introduction
* Involves the computation of stresses and strain resulting from the loads in order to establish whether or not the structure is able to withstand them.
* Only two types of stress can result:
    * Normal stress: acts perpendicular to the cross-section.
    * Shear Stress: acts tangentially to the cross-section.
## 2:Normal stress and strain
### 2.1:Normal Stress
* The simplest definition of stress is the force per unit area.
* $\sigma=\displaystyle\frac{F}{A}$
* All materials have their own characteristics, which determine the maximum stress they can safely withstand.
* Normal strain can be defined as the effect of applying a tensile force to a section of material.
* A sign convention is adopted that tensile stresses as positive and compressive as negatives.
* -
* -
### 2.2: Normal Strain
* $\epsilon=\displaystyle\frac{\Delta L}{L}$.
* -
* -
## 3:Shear Stress and Strain 
### 3.1 Shear Stress
* Those acting tangentially to the cross section of a material.
* -
* -
* -
* -
* The shear stress is defined as shear force(V) divided by shear area(A): $\tau=\displaystyle\frac{V}{A}$
### 3.1 Shear Strain
* Shear Strain is defined as the change in angle (radian) between two originally mutually perpendicular edges: $\gamma=\displaystyle\frac{\delta}{h}$, where $\delta$ is the change in length and h is the unchanged length.
## 4:Mechanical properties of material and stress-strain relationship (Hooke's Law)
### 4.1 Stress-Strain Curve
* The stress-strain curve of materials can be determined using tensile test.
* -
* -
* -
* Many materials exhibit a linear stress-strain relationship foe low  values of stress.This relationship of stress being directly proportional to strain is know is Hooke's Law:
$\omega=E\epsilon$, where E is referred as modulus or Young's modulus.
* Materials used in engineering can be classified as being ductile or brittle: 
    * In the stress-strain curve, ductile materials can undergo large strains under load before facture occurs, which have a noticeable change in the cross-section (necking) due to the approaching of the fracture(or failure).
    * In contrast, brittle materials deform little before fracture, can fail suddenly without any sign.
       * -
       * -
       * -
### 4.2 Elastic Constants
* Young's modulus, the shear modulus and Poisson's ratio($\nu$) are termed as elastic constants which have such relationship:
$$
G=\displaystyle\frac{E}{2(1+v)} 
$$
* Young's modulus, E, can be written as :
$$
E=\displaystyle\frac{\sigma}{\epsilon}
$$
This relationship only applies to linear region of the curve.
* Some typical values of Young's modulus:
    * -
    * -
    * -
* Shear modulus, G, is also know as rigidity and can be defined as:
$$
G=\displaystyle\frac{\tau}{\gamma}
$$
* Poisson effect / Poisson's ratio: each materials has a property termed Poisson's ratio,$\nu$, which is the ratio of lateral strain to longitudinal strain in the elastic region of the curve:
$$
\nu=-\displaystyle\frac{\varepsilon_y}{\varepsilon_x}
$$
The negative sign in the expression above ensures $\nu$ is positive.
* These are some typical values of Poisson's ratio:
    * -
    * -
    * -
## 5:Factor of safety
* For materials defined as ductile, factor of safety is defined as :
$$
n_{ductile}=\displaystyle\frac{yield\quad stress}{applied\quad stress}=\displaystyle\frac{\sigma_{ult}}{\sigma_{applied}}
$$
* For brittle materials, the factor of safety can be determined as:
$$
n_{brittle}=\displaystyle\frac{\sigma_{ult}}{\sigma_{applied}}
$$
* For any type of material, if n<=1, then failure(i.e. yielding for ductile materials and fracture for brittle materials) will occur.