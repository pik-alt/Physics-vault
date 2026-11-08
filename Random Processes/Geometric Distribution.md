

If we have a random process that has only two outcomes, success and fail:

$\text{"Success" has probability }p,$
$\text{"Failure" has probability } 1-p=q$

Each trial must also be independent for us to use a geometric distribution.

**The geometric distribution gives us the probability of x failures before the first success.**

$P_{n} = q^np$


#### Calculating the expected value of the geometric distribution
(I don't know if this is examined or not)

$$
\langle x \rangle = \displaystyle \sum_{n=0}^\infty npq^n \\
\\
pq \displaystyle \sum_{n=0}^\infty nq^{n-1} \\
\\
\frac{d}{dx} q^n = nq^{n-1} \therefore \\
\\
\langle x \rangle = pq \frac{d}{dx} \displaystyle \sum_{n=0}^\infty q^n \\
\\
\langle x \rangle  = pq \frac{d}{dx} \frac{1}{1-q} = pq \frac{1}{(1-q)^2} = \frac{q}{p}

$$

$Var(x) = \frac{1-p}{p^2}$


Note: This distribution has no "memory", what happened before does not affect anything that's happening afterwards.