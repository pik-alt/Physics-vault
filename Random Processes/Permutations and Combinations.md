
**Permutations are ways to arrange items in a set, with each ordering being it's own permutation**

**Combinations are like permutations, except they don't care about order**

$\text{Permutations } > \text{Combinations}$


## Permutations

If you want to order $n$ items, then there are $n!$ permutations.

If we want a subset of $m$ items where $m<n$ , we just stop early.
We'd go all the way to $n-(m-1)$ choices. (which equates to $(n-m+1)$)

We give permutations the symbol ${}^nP_{m}$, where n is the number of items and m is how many we want.


We can then show that ${}^nP_{m} \times (n-m) \times (n-m-1) \dots \times 1 = n!$

$\therefore {}^nP_{m} \times (n-m)! = n!$

${}^nP_{m} = \frac{n!}{(n-m)!}$


## Combinations

In combinations, order doesn't matter unlike in permutations.

Each combination appears $m!$ times in the list of permutations, as there are $m!$ number of re-arrangements.

so: ${}^nC_{m} = \frac{n!}{(n-m)!m!}$

