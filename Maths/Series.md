
## Arithmetic Series

$u_{n+1} = u_{n} + d$
$u_{n}=u_{1} + (n-1)d$

$d = \text{Common difference}$

$S_{N} = \frac{1}{2}N(u_{1}+u_{N})$


## Geometric Series

$u_{n+1} = ru_{n}$
$u_{n}=ar^n$

$S_{N} = \frac{u_{0}(1-r^{N+1})}{1-r}$


n runs from 0 to N.



### $N\to \infty$

If $|r| \geq 1,$ the series diverges.

If $|r| < 1,$ the series converges.

$S_{\infty} = \frac{u_{0}}{1-r}$

## Binomial Series

Binomial series is the name given to any expansion of $(a+b)^n$

If n is a positive integer, then the expansion looks like:

$\displaystyle \sum_{r=0}^{n} \frac{n!}{r!(n-r)!}a^{n-r}b^r$


So it will look something like:

$a^n + na^{n-1}b + \frac{n(n-1)}{2!}a^{n-2}b^2 +\dots + b^n$

$\binom{n}{0}a^nb^0 + \binom{n}{1}a^{n-1}b^1 + \binom{n}{2}a^{n-2}b^2$

and in general:

$\binom{n}{r}a^{n-r}b^r$


When dealing with something in the form $(a+x)^n$ then there's a useful case to remember:

$1 + nx + \frac{1}{2!}n(n-1)x^2 + \frac{1}{3!}n(n-1)(n-2)x^3 \dots$


When $|x| < 1$, the series converges for a negative power, which means that you can approximate $(1+x)^n |_{|x|\ll 1} \approx 1+nx$


## Taylor Series

if $f(x)$ is single valued, continuous and differentiable N times, then it can be approximated by a polynomial of N+1 terms at any point in the function's domain, $x=a$.

$f(x) \approx f(a) + \frac{f'(a)}{1!}(x-a) + \frac{f''(a)}{2!}(x-a)^2 + \dots + \frac{f^{(N)}(a)}{N!}(x-a)^N$


If $f(x)$ is differentiable to infinite order, then you can exactly describe it with:

$f(x) = \displaystyle \sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n$


This means that if we know the value of a function and all of it's derivatives at any given point, then we know what the whole function must look like.


## Maclaurin Series

If we perform the Taylor series expansion at the point x = 0:

$f(x) = \displaystyle \sum_{n=0}^{\infty} \frac{x^n}{n!}f^{(n)}(0)$


## Partial Taylor Series

If we have a function $f(x,y)$, we can still do a Taylor Series expansion, it just looks like a messy piece of shit.

$f(x,y) = f(x_{0},y_{0}) +(x-x_{0}) \frac{ \partial f }{ \partial x } + (y-y_{0})\frac{ \partial f }{ \partial y } + \frac{1}{2}(x-x_{0})^2 \frac{ \partial^2 f }{ \partial x^2 } + \frac{1}{2}(y-y_{0})^2\frac{ \partial^2 f }{ \partial y^2 } + (x-x_{0})(y-y_{0})\frac{ \partial^2 f }{ \partial x \partial y }$



## L'Hôpital's rule

If you have a weird indeterminate limit like $\lim_{ x \to 0 } \frac{\sin(x)}{x}$, if the two functions are differentiable, then if there's some point $x=a$ where:

$\displaystyle \lim_{ x \to a }f(x) = \displaystyle \lim_{ x \to a }g(x)=0$:

$\displaystyle \lim_{ x \to a } \frac{f(x)}{g(x)} = \frac{f'(a)}{g'(a)}$



