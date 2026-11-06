
**The exponential distribution governs waiting times between independent random events, which have a known average rate of occurrence.**

e.g.
- time between radioactive decays (they love this one)
- waiting times in a queue
- how long before a device fails

It doesn't have to be a time, but it has to be continuous.


For events occurring at a typical rate $\lambda$, the probability of it happening during a small time interval $\delta t$ is:

$P(\text{event}) = \lambda\delta t,  P(\text{no event}) = 1-\lambda\delta t$

after $n$ time windows:

$P(\text{no event}) = (1-\lambda\delta t)^n$

$t=n\delta t, \therefore \delta t=\frac{t}{n}$

$P(T>t) = \left( 1-\lambda\frac{t}{n} \right)^n$

take the limits...

$\lim_{ n \to \infty } (1-\frac{\lambda t}{n})^n = e^{-\lambda t}$


CDF = area under the graph = $1-e^{-\lambda t}$
PDF = $\lambda \exp(-\lambda t)$

$\text{ only for }t\geq 0$


---
This distribution also has no "memory", the chances of something happening 5 times after it has already happened 2 times is just the same as the probability of it happening 3 times.

There's a quite long derivation for the next properties that I really don't feel like writing out.

$\langle x \rangle = \frac{1}{\lambda}$

$\sigma = \frac{1}{\lambda} = \langle x \rangle$

$\text{ half life = }t_{\frac{1}{2}} = \frac{\ln 2}{\lambda} = \text{ time for half of the random events to happen}$



