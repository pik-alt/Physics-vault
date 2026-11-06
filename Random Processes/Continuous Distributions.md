
If $X$ can take on any continuous value, such as any real number, then asking $p(X=x)$ doesn't make any sense, however we *can* talk about $p(x_{0} < X <x_{1})$

We can define the **Probability Density Function (PDF)** of a continuous distribution like so:

$f(x) = \frac{P(x < X < x+\delta x)}{\delta x}$

which we can then use to work out $P(x_{1}<X<x_{2})$ by integrating:
$\int_{x_{1}}^{x_{2}}f(x)dx$, this means that the probability is the area under the PDF.


---
Important properties of PDFs:

1. $\int_{-\infty}^\infty f(x)dx = 1$
2. $f(x) = 0$ everywhere
3. PDFs have units


---
Expected Values:

$\langle X \rangle = \int_{-\infty}^\infty xf(x)dx$

$\langle g(X) \rangle = \int_{-\infty}^\infty g(x)f(x)dx$

The variance (and so by extension standard deviation) are the same as in a discrete distribution.



## Uniform Distribution

The PDF for a uniform distribution is:

$f(x) = c; a\leq x \leq b \newline f(x)=0; \text{Otherwise}$


![[Uniform probability function.png|501]]

*An example of a uniform distribution*

For it to be normalised: $c=\frac{1}{b-a}$

The expected value $\langle x \rangle = \frac{1}{2}(a+b)$

$Var(X) = \frac{1}{12}(b-a)^2$


## Cumulative Distribution Function (CDF)

Written as c, it is:

$c = \int_{-\infty}^\infty f(x)dx$

It adds up the area under the graph and plots it for any given x.

![[cumulative uniform function.png|515]]

*The CDF for the above uniform distribution*

$c(x) = 0: x<a$
$c(x) \to 1 \text{ as } x\to \infty$


