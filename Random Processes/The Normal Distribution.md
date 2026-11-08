
The PDF for the Normal distribution is:
$\frac{1}{\sqrt{ 2\pi }\sigma}\exp\left( -\frac{(x-\mu)^2}{2\sigma^2} \right)$

Which is often written as:

$\cal{N}(\mu,\sigma^2)$

![[Normal Distribution.png]]

*Normal Distribution for mu = 0 and sigma = 1*


To find the values of $P(X>a) \text{ or } P(X<b)$, for example, we need to integrate this function, however this has no analytical solution, meaning we need to do some maths wizardry and find it numerically which a lot of other smart people have already done and provided us with a table.

![[table of cum. normal dist.png|476]]

*This table is scaled for $\mu=0 \text{ and }\sigma=1$

This is given the name of $C(x)$

$\therefore \int_{a}^b f(x)dx = C(b)-C(a)$

If you have a problem where either $\mu \neq 0 \text{ and/or } \sigma \neq 1$, you can scale it with the following:

$Z=\frac{X-\mu}{\sigma}$, where $Z$ is the value given in the table.

> Example:
> $\mu=161.9, \sigma=6.5, \text{ what is }P(X>180)?$
> 
> $Z=\frac{X-\mu}{\sigma} = \frac{180-161.9}{6.5} = 2.785$
> 
> $P(Z>2.785) = 1-C(2.8) [\text{2.8 is the closest table value}] = 0.00256$
> 


## The Central Limit Theorem

For **any** independent variable X with mean $\mu$ and variance $\sigma^2$, if y is the mean of n values drawn from X,
i.e. $y=\frac{1}{n}\displaystyle \sum_{i=1}^nX_{i}$
Then the values of y are normally distributed:

$\cal{N}\left( \mu, \frac{\sigma^2}{n} \right)$

If you're calculating the mean of the values drawn from X, then $\sigma^2_{y} = \frac{\sigma^2}{n}$ and $\mu_{y}=\mu$
where $n$ is the sample size, for example if you generate 20 values 100 times, $n=20$.

If you're working with sums instead of means:

i.e. $Z=\displaystyle \sum_{i=1}^n\newline Z=\cal N(n\mu,n\sigma^2)$

The values from $X$ do not have to be evenly or uniformly distributed, as long as they have a mean and variance, they will eventually form a standard deviation.




