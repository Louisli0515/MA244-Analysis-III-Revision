# MA244-Analysis-III-Revision
Personal revision on MA244 Analysis III, learn from tutorial sheet and past papers.

So this repository will mainly focus on two parts, support class questions and past papers. I will provide the pdf made by myself so there will not be any problems about license. 


## Lecture notes

The most important part is of course the lecture notes, feel free to download the 2022 version.

[Notes-Analysis-III-JLR-2022.pdf](https://github.com/Louisli0515/MA244-Analysis-III-Revision/files/11045431/Notes-Analysis-III-JLR-2022.pdf)

## Support Class questions

Below are all the support class questions I have done, and it is divided into weekly sections, feel free to download the complete version created by myself.

### Week 2

[MA244_Analysis_III_week2.pdf](https://github.com/Louisli0515/MA244-Analysis-III-Revision/files/11045440/MA244_Analysis_III_week2.pdf)

In week 2's support class questions, the most important concept is Riemann integrable. 

#### Riemann integrable

* Let $f:\left[a,b\right]\to\mathbb{R}$ be a bounded function. Then $f$ is integrable if and only if for every $\varepsilon > 0$, there exists a partition $P$ of $\left[a,b\right]$ such that $$U(f,P) - L(f,P) < \varepsilon.$$ 
* Intuitively, $$L(f,P)\leq \int_{a}^{b}f\leq U(f,P).$$

Don't forget refinement as well!!!

#### Refinement

* A partition $Q = \set{J_{1},...,J_{l}}$ of $\left[a,b\right]$ is a refinement of a partition $P = \set{I_{1},...,I_{n}}$ if every interval $I_{k}$ in $P$ is the union of one or more intervals $J_{k}$ from the partition $Q$.

### Week 3

[MA244_Analysis_III_week3.pdf](https://github.com/Louisli0515/MA244-Analysis-III-Revision/files/11056946/MA244_Analysis_III_week3.pdf)

In week 3's support class questions, there are some theorems that is worth investigating.

#### Intermediate Value Theorem

* If $f:[a,b]\to\mathbb{R}$ is continuous, then if $u$ is a number between $f(a)$ and $f(b)$, that is $$\min (f(a),f(b))\leq u\leq\max((f(a),f(b)),$$ then there exists a $c\in[a,b]$, such that $$f(c) = u.$$

#### Uniform continuity

* A function $f:\Omega\subset\mathbb{R}\to\mathbb{R}$ is uniformly continuous if for every $\varepsilon>0$, there exists a $\delta = \delta(\varepsilon)$, such that $$\left|x-y\right|<\delta\implies\left|f(x)-f(y)\right|<\varepsilon.$$

Something really obvious but needs to be remembered:

#### Reverse Triangle Inequality

* Consider two elements $a,b$, we have $$\left|\left|a\right|-\left|b\right|\right|\leq\left|a-b\right|.$$
#### Triangle Inequality

* Consider two elements $a,b$, we have $$\left|a+b\right|\leq\left|a\right|+\left|b\right|.$$

### Week 4

[MA244_Analysis_III_week4.pdf](https://github.com/Louisli0515/MA244-Analysis-III-Revision/files/11062629/MA244_Analysis_III_week4.pdf)

In week 4's support class questions, the topic is more about improper integrals.

#### Improper integral

* Let $f:(a,b]\to\mathbb{R}$ be a Riemann integrable function for every $[c,b]$ with $a < c$. Then the improper integral of $f$ on $[a,b]$ is defined as $$\int_{a}^{b}f(x)\mathrm{d}x = \lim_{\varepsilon\to0^{+}}\int_{a+\varepsilon}^{b}f(x)\mathrm{d}x.$$

#### Logarithm inequalities

* For $x \geq 1$, we have $$\log (x) \leq x-1.$$

### Week 5

[MA244_Analysis_III_week5.pdf](https://github.com/Louisli0515/MA244-Analysis-III-Revision/files/11080557/MA244_Analysis_III_week5.pdf)

In week 5's support class questions, there are two main focuses: pointwise convergence and uniform convergence.

#### Pointwise convergence

* Let  $\left(f_{n}\right)$ be a sequence of functions with $f_{n}$ : $\Omega \to \mathbb{R}$. We say that $(f_{n})$ or $f_{n}$ converges pointwise to $f:\Omega\to\mathbb{R}% if and only if for every $x\in\Omega$, we have $$\lim_{n\to\infty}f_{n}(x) = f(x).$$

#### Uniform convergence

* Let $f_{n}:\Omega\to\mathbb{R}$ be a sequence of functions. We say that $(f_{n})$ converges uniformly to $f:\Omega\to\mathbb{R}$ if and only if for every $\varepsilon>0$ there exists $N(\varepsilon)$ such that $$\left|f_{n}(x) - f(x)\right|<\varepsilon$$ for every $x\in\Omega$ and for all $n>N(\varepsilon).$
* Its notation is $$f_{n}\rightrightarrows f.$$
* Also, we can have a simplier version: $$f_{n}\rightrightarrows f \leftrightarrow \forall\varepsilon > 0,\exists N(\varepsilon)\, s.t. \sup_{x\in\Omega}\left|f_{n}-f\right|<\varepsilon \, \forall n> N(\varepsilon).$$

#### Relationship between pointwise and uniform convergence

* Uniform convergence implies pointwise convergence. The converse if false and the example is given in **Page 22 in Notes** and **2(a) in Support class problems**. 

### Week 6

[MA244_Analysis_III_week6.pdf](https://github.com/Louisli0515/MA244-Analysis-III-Revision/files/11070485/MA244_Analysis_III_week6.pdf)

In week 6's support class questions, we need to remember the following theorems we learnt in 1st year.

#### Epsilon-delta definition of limits

* We say a function f has a limit at infinity, if there exists a real number $L$ such that for all $ε>0$, there exists $N>0$ such that $$\left|f(x)−L\right|<ε$$ for all $x>N$. In that case, we write $$\lim_{x\to\infty}f(x)=L.$$

#### Mean Value Theorem

* If $f$ is a continuous function on a closed interval $\left[a,b\right]$ and differentiable on the open interval $(a,b)$, then there exists a point $c\in(a,b)$ such that $$f'(c) = \frac{f(b)-f(a)}{b-a}.$$

#### Convergence

* Remember $$\sum_{n=1}^{\infty}\frac{1}{n^{p}}$$ converges when $p>1$.

#### Weierstrass M-test

Suppose that $(fn)$ is a sequence of real or complex-valued functions defined on a set A, and that there is a sequence of non-negative numbers $(M_{n})$ satisfying the following conditions:

* $\left|f_{n}(x)\right|\leq M_{n}$, for all $n\geq 1$ and $x\in A.$
* $\displaystyle\sum_{n=1}^{\infty} M_{n}$ converges.

Then the series $$\sum_{n=1}^{\infty}f_{n}(x)$$ converges abosultely and uniformly on $A$.

#### Uniform convergence imply continuity

* Assume that $f_{n}$ converges uniformly to $f$ on $C$ and that each $f_{n}$ is uniformly continuous on $C$, then $f$ is uniformly continuous on $C$.

The proof is easy. $$\left|f(x)-f(y)\right|\leq\left|f(x)-f_{n}(x)\right|+\left|f_{n}(x)-f_{n}(y)\right|+\left|f_{n}(y)-f(y)\right|.$$

#### Uniformly Cauchy

* A sequence $(f_{n})$ of functions in $\Omega$ is called uniformly Cauchy if and only if for every $\varepsilon > 0$, there exists $N(\varepsilon)$ such that $\left\||f_{n}-f_{m}\right\||_{\infty} < \varepsilon$ for all $n,m>N(\varepsilon)$.
* A sequence $(f_{n})$ is uniformly covergent if and only if it is uniformly Cauchy.

#### Continuity and uniformly convergence

* Let $(f_{n})$ be a sequence of $C^{1}$ functions on $[a,b]$. Assume $f_{n}\to f$ in the pointwise sense and $f_{n}'\rightrightarrows g$. Then $f$ is $C^{1}$ and $g = f'$ or $f_{n}'\rightrightarrows f'$.

### Week 7

[MA244_Analysis_III_week7.pdf](https://github.com/Louisli0515/MA244-Analysis-III-Revision/files/11073170/MA244_Analysis_III_week7.pdf)

In week 7's support class, these two theroems are still need to be mainly focused on.

#### Weierstrass M-test

Suppose that $(fn)$ is a sequence of real or complex-valued functions defined on a set A, and that there is a sequence of non-negative numbers $(M_{n})$ satisfying the following conditions:

* $\left|f_{n}(x)\right|\leq M_{n}$, for all $n\geq 1$ and $x\in A.$
* $\displaystyle\sum_{n=1}^{\infty} M_{n}$ converges.

Then the series $$\sum_{n=1}^{\infty}f_{n}(x)$$ converges abosultely and uniformly on $A$.

#### Continuity and uniformly convergence

* Let $(f_{n})$ be a sequence of $C^{1}$ functions on $[a,b]$. Assume $f_{n}\to f$ in the pointwise sense and $f_{n}'\rightrightarrows g$. Then $f$ is $C^{1}$ and $g = f'$ or $f_{n}'\rightrightarrows f'$.

### Week 8

[MA244_Analysis_III_week8.pdf](https://github.com/Louisli0515/MA244-Analysis-III-Revision/files/11087289/MA244_Analysis_III_week8.pdf)

In week 8's support class, we are entering Complex Analysis and the main focus is Cauchy-Riemann equation and Series convergence.

#### Cauchy - Riemann equations

* Assume that $f(z) = u(x,y)+iv(x,y)$ for $z = x+ iy$. Then the Cauchy-Riemann equations are given by $$u_{x} = v_{y},\qquad u_{y} = -v_{x}.$$

#### Series Convergence test

* Given a sequence $(a_{n})$, there exists $R\in\left[0,\infty\right]$ called the radius of convergence such that $$\sum_{n=0}^{\infty}a_{n}z^{n}$$ converges for all $\left|z\right| < R$ and diverges for $\left|z\right| > R$.
* There is a formula for finding such $R$, $$R = \frac{1}{\displaystyle\lim_{n\to\infty}\sup\left|a_{n}\right|^{\frac{1}{n}}}.$$
* Ratio test (**first version**): Consider $\displaystyle\sum_{n=0}^{\infty}a_{n}$ and assume that $a_{n}\ne 0$ for all $n$. Then 1. If $\lim\sup\frac{|a_{n}+1|}{|a_{n}|} < 1$, then $\displaystyle\sum_{n=0}^{\infty}a_{n}$ is convergent; 2. If $\frac{|a_{n+1}|}{|a_{n}|}\geq 1$ for all $n>N$, then $\displaystyle\sum_{n=0}^{\infty}a_{n}$ is divergent.
* Ratio test (**second version**): Let $a_{n}\ne 0$ for all $n\geq N$, and assume that $\displaystyle\lim_{n\to\infty}\frac{|a_{n+1}|}{|a_{n}|}$ exists. Then $\displaystyle\sum_{n=0}^{\infty}a_{n}z^{n}$ has radius of convergence $$R = \lim_{n\to\infty}\frac{|a_{n}|}{|a_{n+1}|}.$$

### Week 9

[MA244_Analysis_III_week9.pdf](https://github.com/Louisli0515/MA244-Analysis-III-Revision/files/11102697/MA244_Analysis_III_week9.pdf)

In week 9's support class, the main focus is still about Cauchy-Riemann equations and its applications. Apart from that, there are still some more theorems to check.

#### Cauchy's Theorem

* Let $f:\Omega\to\mathbb{C}$ be an analytic function, with $\Omega$ an open, simply connected domain. Let $\gamma$ be a $C^{1}$ closed curve in $\Omega$. Then $$\int_{\gamma}f(z)\mathrm{d}z = 0.$$

#### Parametrisation of a line

* Techniques: Since we are in complex analysis area, remember the parametrisation of $z$ always sticks to $z = x+iy$. For example, when you are trying to parametrise a line $y = x$, we rewrite $z$ as $e^{i\theta}$. Note when $t\in[0,1]$, $\left|z\right|$ should move from 1 to 0 (assume counter-clockwise). Hence the first part of the parametrisation should be $(1-t)$ (the choice of $\theta$ would not affect $\left|z\right|$ as $\left|e^{i\theta}\right| = 1$.).
* For $y = x$, the line makes $\frac{\pi}{4}$ to the $x$-axis, so $\theta = \frac{\pi}{4}$ in this case. 
* Therefore, the final parametrisation is $z = (1-t)e^{i\frac{\pi}{4}}$.

#### Parametrisation of a circle

* Techniques: This is fairly straightforward, the parametrisation should be $$z = Re^{it},\quad t\in[0,2\pi].$$
* If the question is asking to calculate $$I = \frac{1}{2\pi i}\int_{\partial B_{r}(0)} f(z)\mathrm{d}z,$$ where $f:z\to\displaystyle \sum_{n=0}^{\infty}a_{n}z^{n},$ subsutitute the parametrisation and do the normal integral. Note there might be a involve of **Kroneck Delta**.

#### Kroneck Delta

* The Kroneck Delta is defined as when $i\ne j$,  $$\delta_{ij} = 1, $$ when $i = j$, $$\delta_{ij} = 0.$$ 

### Week 10

[MA244_Analysis_III_week10.pdf](https://github.com/Louisli0515/MA244-Analysis-III-Revision/files/11105652/MA244_Analysis_III_week10.pdf)

In week 10's support class, the main focus is still Cauchy's formula. However there are more to look at.

#### Cauchy's formula

* Let $\gamma:\left[a,b\right]\to\mathbb{C}$ be a positively oriented simple closed $C^{1}$ curve. Assume that $f$ is analytic in $\gamma$ and on the interior of $\gamma$, $I(\gamma)$. Then $$f(z) = \frac{1}{2\pi i}\int_{\gamma}\frac{f(w)}{w-z}\mathrm{d}w,\qquad \forall z\in I(\gamma).$$

#### Maximum modulus principle

The following is only a small part of the principle:

* Let $f$ be an analytic function in $B_{r}(z)$ for some $r>0$ and $z\in\mathbb{C}$, and we parametrise $z = a+re^{it}$, then $$\int_{0}^{2\pi} \left|f(z+re^{i\theta})\right|\mathrm{d}\theta \leq \max_{\theta}\left|f(z+re^{i\theta})\right|\int_{0}^{2\pi}\mathrm{d}\theta.$$
* The reason for the above inequality is although $\displaystyle\max_{\theta}\left|f(z+re^{i\theta})\right|$ involves $\theta$ which should be integrated, it is a constant so we can put it outside the integral.

#### Taylor Series Expansion Theorem

* Let $f$ be an analytic function on $B_{R}(a)$ for $a\in\mathbb{C}$, $R>0$. Then there exists unique constants $c_{n}, n\in\mathbb{N}$ such that $$f(z) = \sum_{n=0}^{\infty}c_{n}(z-a)^{n}\qquad\forall z\in B_{R}(a).$$ Moreover, the coefficients $c_{n}$ are given by $$c_{n} = \frac{1}{2\pi i}\int_{\gamma}\frac{f(w)}{(w-a)^{n+1}}\mathrm{d}w = \frac{f^{(n)}(a)}{n!}.$$

#### Liouville's Theorem

* Let $f:\mathbb{C}\to\mathbb{C}$ be an analytic, bounded function. Then $f$ is constant.
