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

### Week 4

[MA244_Analysis_III_week4.pdf](https://github.com/Louisli0515/MA244-Analysis-III-Revision/files/11062629/MA244_Analysis_III_week4.pdf)

In week 4's support class questions, the topic is more about improper integrals.

#### Improper integral

* Let $f:(a,b]\to\mathbb{R}$ be a Riemann integrable function for every $[c,b]$ with $a < c$. Then the improper integral of $f$ on $[a,b]$ is defined as $$\int_{a}^{b}f(x)\mathrm{d}x = \lim_{\varepsilon\to0^{+}}\int_{a+\varepsilon}^{b}f(x)\mathrm{d}x.$$

#### Logarithm inequalities

* For $x \geq 1$, we have $$\log (x) \leq x-1.$$

### Week 5

In week 5's support class questions, there are two main focuses: pointwise convergence and uniform convergence.

#### Pointwise convergence

* Let $ (f_{n})_{n=1}^{\infty} $ be a sequence of functions with $f_{n}$ : $\Omega \to \mathbb{R}$. We say that $(f_{n})$ or $f_{n}$ converges pointwise to $f:\Omega\to\mathbb{R}% if and only if for every $x\in\Omega$, we have $$\lim_{n\to\infty}f_{n}(x) = f(x).$$
