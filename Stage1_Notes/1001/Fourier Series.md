# VI: Fourier Series
## 1: Periodic functions and Fourier Series representation
### 1.1 Periodic Functions
* The pattern that repeat themselves in the period of $t$ or $x$.
* These functions can be interpreted as a sum of sine and/or cosine, i.e the sum of the frequencies.
* The mix of the frequencies makes the voice and the sound.
* The combining of sine and cosine components is called Fourier synthesis.
* Breaking down the function into components is called Fourier Analysis.
### 1.2 Representing a function using harmonic functions
* The most of the function we considered have the period of $2\pi$.
* Let:
$$
f(t)=C+a_1\cos(t)+a_2\cos(2t)+.....+b_1sin(t)+b_2\sin(2t)...
$$
$$
i.e:
f(t)=\displaystyle\frac{a_0}{2}+\sum_{n=1}^\infin[a_n\cos(nt)+b_n\sin(nt)]
$$
* The term C represent the mean value of the function (DC component in oscillation)
### 1.3 Finding the coefficient
* To find the coefficient term, we calculated the mean value of $f(t)$, i.e.$C=\displaystyle\frac{a_0}{2}=\displaystyle\frac{1}{2\pi}\int_{-\pi}^{\pi}f(t)dt$
* The way to solve the components is to multiply $\cos(t)$ in both sides of the $f(t)$.
* Then integrate both sides in $[-\pi ,\pi]$.
* Cause the integration of $\cos(t)$ in the range $[-\pi , \pi]$ =0.
* So we can find that:
$a_1=\displaystyle\frac{1}{2\pi}\int_{-\pi}^{\pi}f(t)\cos(t)dt$
* It is clear that we can find the related component by multiply the related cos or sin.
* The final solutions:
 $$
 \displaystyle\frac{a_0}{2}=\displaystyle\frac{1}{2\pi}\int_{-\pi}^{\pi}f(t)dt
 $$
$$
a_n=\displaystyle\frac{1}{\pi}\int_{-\pi}^{\pi}f(t)\cos(nt)dt
$$
$$
b_n=\displaystyle\frac{1}{\pi}
$$
### 1.4 Examples
#### 1.4.1 The square wave
* $f(t)=-2$ if $-\pi \leq t<0$
* $f(t)=2$ if $0\leq t\leq \pi$
* This a odd function, so we need sine only.($a_n=0$)
* $b_n=\displaystyle\frac{1}{\pi}\int^{\pi}_{-\pi}f(t)\sin(nt)dt$
* $b_n=\displaystyle\frac{8}{n\pi}$ if n is odd or =0 if n is even.
* $f(x)=\displaystyle\frac{8}{\pi}\sum_{m=1}^{\infin}\displaystyle\frac{1}{(2m-1)}\sin(2m-1)t$
* We look at the partial sum and the discontinuity of this function.
#### 1.4.2 $f(t)=t^2$ on the interval $[-\pi,\pi]$
* $f(t)$ is a even, so only cosines are needed, and $b_n=0$
* 
$$
\displaystyle\frac{a_0}{2}=\displaystyle\frac{1}{2\pi}\int_{-\pi}^{\pi}t^2 dt=\displaystyle\frac{\pi ^2}{3}
$$
* $a_n=\displaystyle\frac{1}{\pi}\int_{-\pi}^{\pi}t^2\cos(nt)dt=\displaystyle\frac{4}{n^2}(-1)^n$
* So the final form of the Fourier Series is:
$$
f(x)=\displaystyle\frac{\pi ^2}{3}+4\sum_{n=1}^{\infin}\displaystyle\frac{(-1)^n}{n^2}
$$
## 2:Complex form of the Fourier Series
* We can combine the cosine and sine to a complex form:$c_n=a_n+ib_n$
* $f(x)=\sum_{-\infin}^{\infin}c_ne^{-inx}$
* $c_n=\displaystyle\frac{1}{2\pi}\int^{\pi}_{-\pi}f(x)e^{inx}dx$
## 3: Other forms of Fourier Series
### 3.1 General interval
* If we use a general interval in $[a,b]$, the series takes this form:
    * $f(t)=\displaystyle\frac{a_0}{2}+\sum_{n=1}^{\infin}a_n\cos(\displaystyle\frac{2\pi nt}{b-a}+b_n\sin(\displaystyle\frac{2\pi nt }{b-a})$
### 3.2: Half-range series
* $f(t)=\sum a_n\cos(nt/2)$
* $f(t)=\sum b_n\sin(nt/2)$
### 3.3 Discrete data
If the function we wish to analyse is discrete points instead of the algebraic function,the numerical integration is needed,while the limited data will come out spurious result.