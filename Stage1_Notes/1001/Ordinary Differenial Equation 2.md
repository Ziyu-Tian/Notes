<!--
# VIII:Ordinary Differential Equations 2
## 1: Ordinary Differential Equations(ODE)
### 1.1: Second order ODE
* The order means the highest order of the derivation.
* The ordinary means that it is about derivation instead of partial differential.
* Such as the Newton's second law:
$$
m\displaystyle\frac{d^2x}{dt^2}=F
$$
## 1.2: Second order,linear,homogeneous ODEs
### 1.2.1 The common format of the second order ODEs
$$ a\displaystyle\frac{d^2y}{dx^2}+b\displaystyle\frac{dy}{dx}+cy=0$$
### 1.2.2 The solution
* Let $y=e^{mt}$ as the trial solution, so the equations can be expressed as $am^2+bm+c=0$, and we can find the value of $m_1$ and $m_2$.
* For three cases:
    * If $m_1$ =$m_2$, the solution will be: $y(t)=Ae^{m_1t}+Be^{m_2t}$.
    * If $m_1$ = $m_2$, the solution will be : $y(t)=Ae^{mt}+Bte^{mt}$.
    * If $m_1$ or $m_2$ =$a+bi$, the solution will be : $y(t)=e^{at}[A\cos(bt)+B\sin(bt)]$
## 1.3: Forced (inhomogeneous), second order, linear ODEs
### 1.3.1: The simple example
$$
a\displaystyle\frac{d^2y}{dt^2}+b\displaystyle\frac{dy}{dx}+cy=F(t)
$$
The $F(t)$ is what we called the forced.
### 1.3.2: The composition of the Inhomogeneous equations
* If the $F(t)$ is equal to 0, which is the free and natural case. This solution is called a **complementary function**.
* If the $F(t)$ is not equal to 0, the solution to this will be a combination of CF and a **response to the forcing**, which is known as **PI** short for **Particular Integration**.
* $y_{GS}(t)=y_{CF}(t)+y_{PI}(t)$
### 1.3.3: The way to find the PI
* Find the trial solution $y(t)$ for the $F(t)$
    * Use constant 'C' to replace the constant in $F(x)$.
    * Keep the constant in the power.
    * Use $A\cos(nx)+B\sin(nx)$ for $\cos(nx)$
* Some examples:
    * $y''+3y'+2y=6$ for $y(t)$
        * Firstly, use $y(t)=C$ as the trial.
        * So $y'=0$ and $y''=0$.
        * Substitute these to the above equations: $0+0+2y=6$
        * So we can find $y(t)=3$
        * The CF of this equation can be find by:
          * $m^2+3m+2=0$, $m_1=-1$ and $m_2=-2$.
          * So $y_{CF}(t)=Ae^{-2t}+Be^{-t}$.
        * The $y_{GS}(t)=Ae^{-2t}+Be^{-t}+3$
    * $y''+5y'+6y=\displaystyle\frac{2}{3}e^{-t}$ and $y(0)=0$,$y'(0)=1$
        *  We can use $Ae^{-t}$ as the trial
        *  So $y'=-Ae^{-t}$ and $y''=Ae^{-t}$.
        *  $Ae^{-t}-5Ae^{-t}+6Ae^{-t}=\displaystyle\frac{2}{3}e^{-t}$, A=$\displaystyle\frac{1}{15}$, $y_{PI}=\displaystyle\frac{1}{3}e^{-t}$    
        *  $m^2+5m+6=0$ , so $m_1$ = -2 and $m_2$= -3. The $y_{CF}=Ae^{-2t}+Be^{-3t}$ 
        *  The  $y_{GS}=Ae^{-2t}+Be^{-3t}+\displaystyle\frac{1}{15}e^{-t}$   
## 1.4: Oscillations & Resonance
### 1.4.1: Resonance
* If forcing “matches” natural/free   behavior of the system we get a “bigger” response -
we call this resonance.
* In maths, the resonance means that the force **F(x)** will be applied on both CF and PI.
### 1.4.2: Find the PI of Resonance
* Resonance is most relevant to oscillatory forcing but the same mathematical idea can be applied on other force.
* The PI of resonance should be multiply a 't' of the ordinary PI.
## 1.5: First order, linear ODEs
### 1.5.1: The Standard form 
$$
\displaystyle\frac{dy}{dt}+p(t)y=q(t)
$$
* $p(t)$ and $q(t)$ are for function of $t$.
* The methods to solve the equations including **integrating factors, separation of variables and substitution.**
### 1.5.2: Integrating Factors
* Firstly, the function should be converted to he standard form.
* $\displaystyle\frac{dy}{dt}+p(t)y=q(t)$
* The **integrating factor** is given by $u(t)=e^{\int p(t)dt}$.
* Multiply the standard function by $u(t)$, then integrating both sides.
* $y(t)=\displaystyle\frac{1}{u(t)}\int u(t)q(t)dt$
* Examples:
    * $y'+2y\sin(2x)=2e^{\cos(2x)}$
        * $u(x)=e^{\int p(x)dx}$, for this situation $p(x)=2\sin(2x)$, $u(x)=e^{\int 2\sin(2x)dx}=e^{2\times(-1)\times0.5\cos(2x)}=e^{-\cos(2x)}$
        * $y(x)=e^{\cos(2x)}\int [e^{-\cos(2x)}\times2e^{\cos(2x)}]=e^{\cos(2x)}(2x+C)$
### 1.5.3: Methods of Substitution
* One standard method is to make the substitution of $y(t)=tv(t)$, where the $v(t)$ is a new function.
* Used in the non-linear 1st ODE, which cannot use the **IF** (not linear) and **separation of  variables** ($\displaystyle\frac{dy}{dx}\not ={y(x)g(y)}$), then use the above methods to solve the equations.
-->
<!--
## 2: Eigenvalues & Systems of Equations
### 2.1: Motivation
* In many engineering applications, we have to solve systems of coupled differential equations.
### 2.2: Linear Geometric Transformations
* If we treat the matrix $A$ as a kind of transformation which could change the **base vectors $i$ and $j$**.
* For some vectors for example $\vec{x}$, the transformation $A$ may not change the direction of $A$, which means it will stay at the linear space it has extended, but its **magnitude may change**.
* In this condition, we may say $Ax=\lambda x$, which means the transformation $A$ is just as a scalar $\lambda$.
### 2.3: Finding the Eigenvalues and Eigenvectors
* The scalar $\lambda$ is called the **eigenvalue**, while the vector $x$ is called the **eigenvector**.
* In order to solve $Ax=\lambda x$, we can change it to $(A-\lambda I)x=0\Rightarrow |A-\lambda I|=0$
-->
### 2.4:Systems of ODE I
Example_1:
     $$
     m_1y''_1=-k_1y_1+k_2(y_2-y_1)
     $$
     $$
     m_2y''_2=-k_2(y_2-y_1)
     $$
     $$
     \begin{pmatrix}
     \ddot{y_1} \\
     \ddot{y_2}
     \end{pmatrix}
     =
     \begin{pmatrix}
     -\frac{(k_1+k_2)}{m_1} & \frac{k_2}{m_1} \\
     \frac{k_2}{m_1} & -\frac{k_2}{m_2} 
     \end{pmatrix}
     \begin{pmatrix}
     y_1 \\
     y_2
     \end{pmatrix}
    $$

* We can take the oscillation (for the second order) :
    * $y_1=c\cos(\omega t-\alpha _1)$
    * $\ddot{y_1}=\omega ^2 y_1$
    * Same for $y_2=\omega ^2 y_2$
    * Any oscillation will got same answer.
    * If we treat that $2\times 2$ matrix as $A$:
    $$
    \omega ^2
    \begin{pmatrix}
    y_1 \\
    y_2 
    \end{pmatrix}
    =
    A
    \begin{pmatrix}
    y_1 \\
    y_2
    \end{pmatrix}
    $$
* It is same as the $Ax=\lambda x$, and the answer of these equations is $x$, which is the eigenvectors.
### 2.5: Systems of ODESs II
$$
    \displaystyle\frac{dx}{dt}=-4x+y
$$
$$
    \displaystyle\frac{dy}{dt}=-5x+2y
$$
$$
    \displaystyle\frac{d}{dt}
    \begin{pmatrix}
    x \\
    y
    \end{pmatrix}=\begin{pmatrix}
    -4 && 1 \\
    -5 && 2 
    \end{pmatrix}
    \begin{pmatrix}
    x \\
    y
    \end{pmatrix}
$$
* Let $\begin{pmatrix}
x \\
y
\end{pmatrix}
=
\begin{pmatrix}
x_0 \\
y_0
\end{pmatrix}
$ $e^{\lambda t}$ 
* $x_0$ and $y_0$ are constant. 
* Then we get:
$$
\lambda
\begin{pmatrix}
x_0 \\
y_0
\end{pmatrix}
=
\begin{pmatrix}
-4 && 1 \\
-5 && 2
\end{pmatrix}
\begin{pmatrix}
x_0 \\
y_0
\end{pmatrix}
$$
* Use the way of E-value and E-vectors can find the solution.
### 2.6: Systems of ODEs III
$$
\dot{x}=x+y-2z
$$
$$
\dot{y}=-x+2y+z
$$
$$
\dot{z}=-y-z
$$
$$
\displaystyle\frac{d}{dt}=\begin{pmatrix}
1&&1&&-2\\
-1&&2&&1\\
0&&-1&&-1
\end{pmatrix}\begin{pmatrix}
x\\
y\\
z
\end{pmatrix}
$$
* Just find the E-vector, the equations can be solved.
## 3: Diagonalisation of matrices and decoupling of systems of equations
* Example:
    $$
    \displaystyle\frac{dx}{dt}=-4x+y
    $$
    $$
    \displaystyle\frac{dy}{dt}=-5x+2y
    $$
* Then:
    $$
    \displaystyle\frac{d}{dt}
    \begin{pmatrix}
    x\\
    y
    \end{pmatrix}=\begin{pmatrix}
    -4&&1\\
    -5&&2
    \end{pmatrix}
    \begin{pmatrix}
    x\\
    y
    \end{pmatrix}
    $$

* If we assumed $y=Pz$
* It is found that $\lambda_1=1$, $x_1=\begin{pmatrix}
1\\
5
\end{pmatrix}$ and $\lambda_2=-3$, $x_2=\begin{pmatrix}
1\\
1
\end{pmatrix}$.
* So $P=\begin{pmatrix}
1&&1\\
5&&1
\end{pmatrix}$ 
* The diagonalisation $Z=P^{-1}AP^{-1}$
* $Z=\begin{pmatrix}
1&&0\\
0&&-3
\end{pmatrix}$
* $\begin{pmatrix}
\dot{z_1}\\
\dot{z_2}
\end{pmatrix}
=Z\begin{pmatrix}
z_1\\
z_2
\end{pmatrix}$
* It is easy to find $z_1=Ae^t$ and $z_2=Be^{-3t}$.
* $y=Pz\Rightarrow\begin{pmatrix}
x\\
y
\end{pmatrix}=
\begin{pmatrix}
1&&1\\
5&&1
\end{pmatrix}
\begin{pmatrix}
z_1\\
z_2
\end{pmatrix}$
* Then the expression of $x$ and $y$ can be found.

    


     




 



