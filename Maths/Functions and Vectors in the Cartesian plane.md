
If you have a non-obvious function that you'd like to plot such as:
$f(x) = \frac{2x^2-3x+3}{x-1}$, you should not down any of the following and then go from there:

- Domain and range
- Asymptotes
- Sign
- Intercepts
- Symmetries

In this example, we can see that the function has an asymptote at $x=1$, so we can plot something like this already:
![[x=1 asymptote.png]]

with the red line being a known asymptote.

Next, we can find out on which side of the asymptote the line approaches on either positive y or negative y by evaluating the numerator at $x=1+\epsilon$, where $\epsilon$ is a very very small value.

The top expands to:
$2 \times (1+\epsilon)^2-3\times(1+\epsilon)+\epsilon$

$2 \times (1^2 + 2x\epsilon + \epsilon^2) -3-3\epsilon + 3$

$2 + 4\epsilon + 2\epsilon^2 - 3\epsilon$
$2+\epsilon \text{  as }\epsilon^2 \text{is negligent}$

so at just above 1, the line is positive because the numerator is positive and the denominator is obviously positive.

The same can be done for the numerator for $f(1-\epsilon)$, where we get a positive numerator and negative denominator, so it's negative.

therefore we can conclude that the line approaches the asymptote something like this:

![[x=1 asymptote drawing.png]]



Next, let's take a look at what happens as x approaches infinity.

For this, we should first divide out the numerator by the denominator due to the numerator's highest power being one above the denominators.  I usually do this by long division but you could do it other ways.

You'd get $2x-1 + \frac{2}{x} + \frac{A}{x^2}\dots$

We can stop evaluating by $\frac{2}{x}$ and the rest because, as $x\to \infty$, all those fractions will approach 0.

We're left with $2x-1$ then, which means that it can be our second asymptote.

And if you excuse the crude drawing, you'd get something like this.

![[2x-1 drawing.png]]


And this is the real plot:


![[full correct function.png]]



## Vectors

For a question like:

$L_{1}= \begin{pmatrix}2\\3\\-4\end{pmatrix} + \lambda \begin{pmatrix}1\\2\\1\end{pmatrix}$

$L_{2}=\begin{pmatrix}0\\9\\-3\end{pmatrix}+\mu \begin{pmatrix}5\\0\\2\end{pmatrix}$

Where you have to evaluate where they meet, you can expand each of the vectors and then solve them as simultaneous equations.

$L_{1}=\begin{pmatrix}2+\lambda\\3+2\lambda\\-4+\lambda\end{pmatrix}$

$L_{2} = \begin{pmatrix}5\mu\\9\\-3+2\mu\end{pmatrix}$

$3+2\lambda=9$
$2~\lambda=6$
$\lambda=3$

So they cross at the point with position vector:

$\begin{pmatrix}2+3\\3+6\\-4+3\end{pmatrix}$

=

$\begin{pmatrix}5\\9\\-1\end{pmatrix}$ = $\vec{c}$



If you need to find the angle between two vectors, you can use the dot product:

$\vec{AC} \cdot \vec{BC} = |\vec{AC}|\times|\vec{BC}|\cos\theta$

To evaluate the dot product:

$\begin{pmatrix}A\\B\\C\end{pmatrix} \cdot \begin{pmatrix}X\\Y\\Z\end{pmatrix} = AX+BY+CZ$




## Even and Odd Function

$f(x)$ is odd if:
$f(-x) = -f(x)$

a.k.a. it's symmetrical from $y=-x$


$f(x)$ is even if:
$f(x) = f(-x)$

a.k.a it's symmetrical between $x=0$








