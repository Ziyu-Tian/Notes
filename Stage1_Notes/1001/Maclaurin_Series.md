# X: Maclaurin Series
## 1: The Exponential, Sine and Cosine Series
### 1.1: An infinite power Series
#### 1.1.1: Introduction
* Consider the infinite Series:
$$
S=1+x+\frac{x^2}{2!}+\frac{x^2}{3!}+\frac{x^4}{4!}+....
$$
* If we differentiate both sides, we can get:
$$
\displaystyle\frac{dS}{dx}=S
$$
* Noting that $\displaystyle\frac{d}{dx}e^x$, so we see that this is the **exponential Series**:
$$
e^x=exp(x)=1+x+\displaystyle\frac{x^2}{2!}+\displaystyle\frac{x^3}{3!}+....
$$
#### 1.1.2: Properties 
* This is a **infinite power series** about $x=0$, which means it works at $x=0$ and nearby.
* The series for $e^x$, converges for all values of $x$, and $x$ can also be complex number.
* We can say it has an **infinite radius of convergence**.
* It works best for small values of $|x|$ or $|z|$.
* A **Maclaurin Series** in a variable $x$ is just a power series about $x=0$.
* The series of cosine, sine and exponential have same derivation way. (Differential)
### 1.2: Using the exponential series
* $e^{10.1}=e^{10}e^{0.1}=e^{10}[1+0.1+\frac{0.01}{2}+ ....]$. If we get the value of $e^{10}$, then we can choose various adaptations of power series like this to get a desired level of accuracy.
* $e^{1+x}=e^1e^x=e[1+x+\frac{x^2}{2} + ....]$
* Using a complex argument is permitted, and the choice of $i\theta$ results in two more useful series: ($\theta $ in radian)
$$
e^{i\theta}=\cos\theta+i\sin\theta=[1-\frac{\theta^2}{2!}+\frac{\theta^4}{4!}- ....]+i[\theta-\frac{\theta^3}{3!}+\frac{\theta^5}{5!}- ...]
$$
* This the power series of $\cos(\theta)$ and $\sin(\theta)$
$$
\cos\theta=1-\frac{\theta^2}{2!}+\frac{\theta^4}{4!}- ....
$$
$$
\sin\theta=\theta-\frac{\theta^3}{3!}+\frac{\theta^5}{5!}- ...
$$
## 2: The Logarithmic Series
* If there is a series like this: $ln(x)=a_0+a_1x+a_2x^2+...$
* If we change another form of this series:
$$
ln(1+x)=x-\frac{x^2}{2}+\frac{x^3}{3}-\frac{x^4}{4}+ ....
$$
* For more usual form, we get **Taylor Series**:
$$
ln(y)=(y-1)-\frac{(y-1)^2}{2}+\frac{(y-1)^3}{3}- ....
$$
* **Taylor Series** is valid near $y=1$, and converges if $0<y\leq 2$. This is a Taylor Series about $y=1$.
* If we differentiate the series, we get: $\frac{1}{1+x}=1-x+x^2-x^3+...$, which is a *geometric series* with first term $a=1$, ratio $r=-x$.
* The geometric series converges if $|x|<1$.
## 3: The Binomial Series
### 3.1: The Binomial Expansion
$$
(a+b)^n=\displaystyle\sum_{r=0}^nC^r_na^{n-r}b^r
$$
* This series is **finite** if $n$ is a positive integer.
### 3.2: The Binomial Series
* If $n$ is negative or a fraction, and we use the same series as above, th series will be **infinite**.
* Firstly, $(a+b)^n=a^n[1+(\frac{b}{a}) ]^n$, then we use the binomial expansion:
$$
(1+x)^p=1+px+\frac{p(p-1)}{2!}x^2+\frac{p(p-1)(p-2)}{3!}x^3+...
$$
* If the power $p$ is a positive integer, the series terminated as before and always convergent.
* If $p$ is negative integer or a fraction, the series is infinite, and converges only if $|x|<1$.
## 4: Applications and Combining series
### 4.1: Combining series
* If we have a function composed of two or more standard series, we can combined, if we correctly identify the overall domain of convergence for the final series.
* For example: 
$$
\begin{align*}
f(x) &=\displaystyle\frac{ln(1-2x)}{\sqrt{1-3x}} \\
&=ln(1-2x)(1-3x)^{-1/2} \\
&=[-2x-2x^2-\frac{8}{3} x^3-...]\times[1+\frac{3}{2}x+\frac{27}{8}x^2+... ] \\  
&=(-2)x+(3-2)x^2+(-\frac{27}{4}+3-\frac{8}{3})x^3+... \\  
\end{align*}
$$
* The combined series will converge if both series converge, so we must satisfy both convergence conditions:
$$
-1<-2x\neq 1\qquad -1<-3x<1
$$
* So $|x|<\frac{1}{3}$ works for both conditions.
### 4.2: Applications for Infinite Series
* Infinite Series can be used to find $e^x$ and $\sin(x)$ in computers.
* Series can be used to evaluate the integral, such as binomial expansion can be used to estimate $\displaystyle\int _0^1\displaystyle\frac{1}{(1+x^2)^3}{\rm d}x$.
* To solve more complicated differential equations.
