---
hide:
  - navigation
  - toc
---

Data sets ($\mathcal{D}$) are categorized into two main groups:

**Synthetic data**  for which the analytical form of the underlying model is known and used to generate data points. <br>
Example: $f(x) = 2x^2 + \cos(x)$<br>
For $x \in [0,1] \rightarrow \mathcal{D}=(x_i,f(x_i))_{i=1}^{n}$. <br>

**Real-world data** for which the underlying model is unknown.<br>

| Category | Underlying model   | Reference | Number of problems | year |
| -------- | ------- | ------- | ------- | ----- 
| Physics | Ordinary differential equations <br> Physics equations (gravity, electromagnetic nuclear, etc. )| [Strogatz repositery](https://williamlacava.com/ode-strogatz/) <br> [Feynman Database](https://space.mit.edu/home/tegmark/aifeynman.html) | 10 <br> 120 | 2011 <br> 2019 |
| <br> <br> <br> Mathematics | <br> <br> <br> monomials, polynomials, <br> trigonometric, exponential, etc.  | koza <br> Keijer <br> Vladislavleva <br> Nguyen <br> Korns <br> R <br> Jin <br> [Livermore](https://arxiv.org/abs/1912.04871) | 3 <br> 15 <br> 8 <br> 12 <br> 15 <br> 3 <br> 6 <br> 22 | 1994 <br> 2003 <br> 2009 <br> 2011 <br> 2011 <br> 2013 <br> 2019 <br> 2021 |
| Real-world | Penn Machine Learning Benchmarks (PMLB) | [Ref](https://epistasislab.github.io/pmlb/) | 122 | -|

## Koza equations
| Dataset | Expression | Variables | Data range|
| -------- | ------- | ------- | ------- |
| Koza-1 | $x^4 + x^3 + x^2 + x$ | 1 |  U[-1, 1, 20] |
| Koza-2 | $x^5 - 2x^3 + x$ | 1 | U[-1, 1, 20] |
| Koza-3 | $x^6 - 2x^4 + x^2$ | 1 | U[-1, 1, 20] |
| Nguyen-1 | $x^3+ x^2 + x$ | 1 | U(-1,1,20)|
| Nguyen-2 | $x^4 + x^3+ x^2 + x$| 1 |  U(-1,1,20)|
| Nguyen-3 | $x^5 + x^4 + x^3+ x^2 + x$| 1 | U(-1,1,20)|
| Nguyen-4 | $x^6 + x^5 + x^4 + x^3+ x^2 + x$ | 1 | U(-1,1,20)|
| Nguyen-5 | $\sin(x^2)\cos(x) -1$ | 1 | U(-1,1,20)|
| Nguyen-6 | $\sin(x) + \sin(x+x^2)$ | 1 | U(-1,1,20)|
| Nguyen-7 | $\log(x+1) + \log(x^2+1)$ | 1 | U(0,2,20)|
| Nguyen-8 | $\sqrt{x}$ | 1 | U(0,4,20)|
| Nguyen-9 | $\sin(x) + \sin(y^2)$ | 2 | U(-1,1,100)|
| Nguyen-10 | $2\sin(x)\cos(y)$ | 2 | U(-1,1,100)|
| Nguyen-11 | $x^{y}$ |  2|
| Nguyen-12 | $x^4 - x^3 + \frac{1}{2}y^2 - y$| 2|
