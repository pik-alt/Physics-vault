
Integration is the opposite function of differentiation

$F(x) = \int f(x) \textrm{d}x$

Then $\frac{dF}{dx} = f(x)$


## Useful rules:

$\displaystyle \int^b_{a}f(x)dx = \displaystyle -\int^a_{b}f(x)dx$


$\displaystyle \int^a_{-a}f(x)\text{d}x = 0; \text{ if } f(x) \text{ is an  }$ [[Functions and Vectors in the Cartesian plane#Even and Odd Function|odd function]].

$\displaystyle \int_{-a}^a f(x)dx = 2 \int^a_{0}f(x)dx;$ if $f(x)$ is an [[Functions and Vectors in the Cartesian plane#Even and Odd Function| even function]].


$$
\displaystyle \int \frac{f'(x)}{f(x)}dx = \ln |f(x)| +c \newline
\\
\int f(x)f'(x)dx = \frac{1}{2}f^2(x)+c
$$



## Integrals with infinities

If the integral could diverge, then you take a limit instead:

$\displaystyle \int^b_{a}f(x) = \lim_{ \varepsilon \to 0 } \int^{b-\varepsilon}_{a}f(x)dx$



## By substitution

Memorise these:

| $f(x)$                         | substitution    | $\displaystyle \int f(x) \, dx$                        |
| ------------------------------ | --------------- | ------------------------------------------------------ |
| $\frac{1}{\sqrt{ a^2 - x^2 }}$ | $x=a\sin\theta$ | $\displaystyle \arcsin\left( \frac{x}{a} \right)+c$    |
| $\frac{1}{\sqrt{ x^2-a^2 }}$   | $x=a\cosh u$    | $\displaystyle \cosh^{-1}\left( \frac{x}{a} \right)+c$ |
| $\frac{1}{\sqrt{ x^2+a^2 }}$   | $x=a\sinh u$    | $\sinh^{-1}\left( \frac{x}{a} \right)+c$               |
| $\frac{1}{x^2+a^2}$            | $x=a\tan\theta$ | $\frac{1}{a}\arctan\left( \frac{x}{a} \right)+c$       |


## Partial Fractions

If we have to integrate a fraction with the top polynomial having one smaller order than the bottom, such as:
$\frac{5x+1}{x^2+3x+2}$, then we can split it into:

$\frac{5x+1}{(x+1)(x+2)} = \frac{A}{(x+1)} + \frac{B}{(x+2)}$.


Solve for $A$ and $B$, then integrate both.

To get the fraction into the correct form, you might have to perform some algebraic long division.



