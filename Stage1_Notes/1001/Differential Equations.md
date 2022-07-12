## 2.Second- order differential equations
### 2.1 Mechanical System with spring and damping

$$
\frac{md^2y}{dt^2}=-ky-C\frac{dy}{dt}
$$
$$
i.e.ma=-F_{restoring}-F_{damp}
$$
It show the relationship between the y and t in the damping system.
#### 2.1.1 Another physical example-an electrical circuit
In a circuit with R,L and C,we can find the voltage relationship:
$$
IR+L\frac{dI}{dt}+\frac{Q}{C}=V(t)
$$
$$
R\frac{dQ}{dT}+L\frac{d^2Q}{dt^2}+\frac{Q}{C}=0
$$
This a second order differential equation.

### 2.2
 Solve the equation

$$
\frac{d^2y}{dx^2}+3\frac{dy}{dt}+2y=0
$$
First, use the $y=e^{mt}$ as a trial solution.

$$
m^2e^{mt}+3me^{mt}+2e^{mt}=0
$$
$$
(m+1)(m+2)=0
$$
$$
m=-1
$$
$$
m=-2
$$
So we have two solutions.

In fact, the GS is 
$$
y=Ae^{-t}+Be^{-2t}
$$
While A, B are the constants.(when A or B=0,ensure containing all the answer)

Then we can use the 
$$
y(0)=1
$$
$$
\frac{dy}{dt}(0)=0
$$
Then we can find the A=2,B=-1.
So the P.S is
$$
y=2e^{-t}e^{-2t}
$$
### 2.3 Quadratic(repeated) roots the same

$$
\frac{d^2y}{dt^2}-2\frac{dy}{dt}+y=0
$$
This gives only one solution:
$y_1=Ae^{-t}$

This case is called the **critical damping**.
However, all second-order d.e.s have two independent solutions.

The other one is 
$$
y_2=Bte^{-t}
$$
So the GS is
$$
y=(A+Bt)e^{-t}
$$
### 2.4 Example of simple harmonic motion
If we choose the simplest case of no damping (R=0), we can find this equations:
$$
\frac{d^2Q}{dt^2}=-\frac{Q}{LC}
$$
This is the simple harmonic motion.
### 2.4.1
Oscillations- complex roots of the auxiliary equations
$$
\frac{d^2y}{dt^2}+2\frac{dy}{dt}+2y=0  
$$

Try $y=e^{mt}
$

We can find that m=$-1\pm i$

So the GS is 
$$
y=Ce^{(-1+i)t}+De^{(-1-i)t}
$$
Next, we use the result:
$$
e^{i\theta}=cos\theta+isin\theta
$$
$$
y=e^{-t}[Acos\theta+Bsin\theta]
$$
We use the final real number to do solve the physical problems.
### 2.6 General Solution for the oscillation equations

If we find $m=\pm Ci+D$;
the GS for real number is:
$$
y=e^{Dx}[Acos(Cx)+Bsin(Cx)]
$$


