**A probability distribution maps all possible outcomes of a random variable to a probability.**

These random variables can either be continuous or discrete.

**A discrete random variable can take on any values from within a countable set of possibilities**.

These are usually written with a capital $X$.

$p_{i} = p(X=x_{i})$

$\forall p_{i}, 0<p_{i} < 1$

$\displaystyle \sum_{i}p_{i} = 1$

all $x_{i}$ are mutually exclusive, e.g. you cannot roll both a 1 and a 6 at the same time with the same dice.

---
### Expected value

The expected value of a random variable is the probability weighted average of all $x_{i}$

$\langle x \rangle = \displaystyle \sum_{i}p_{i}x_{i}$

$\text{as number of samples n} \to \infty, x \to \langle x \rangle$

Similarly:

$\langle x^2 \rangle = \displaystyle \sum_{i}x^2_{i}p_{i}$

In fact:

$\langle f(x) \rangle = \displaystyle \sum_{i}f(x_{i})p_{i}$

**The variance of X is:**
$Var(X) = \langle x^2 \rangle - \langle x \rangle^2$

**The standard deviation of X is:**

$\sigma = \sqrt{ Var(X) }$






