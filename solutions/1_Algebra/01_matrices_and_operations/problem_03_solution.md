# Exercise 3 — Matrices and Basic Operations

## Question

The matrix sizes are

$$
A_{2\times3},\qquad B_{3\times4},\qquad C_{4\times2},\qquad D_{2\times2}.
$$

For the products

$$
AB,\ BA,\ BC,\ CB,\ AC,\ CA,\ AD,\ DA
$$

determine whether they are defined. If so, state the size of the result. Justify each decision using the dimension compatibility condition.

## Solution

A product $X_{m\times n}Y_{p\times q}$ is defined precisely when $n=p$, and the resulting size is $m\times q$.

- $AB$: $2\times3$ times $3\times4$, defined, size $2\times4$.
- $BA$: $3\times4$ times $2\times3$, not defined ($4\ne2$).
- $BC$: $3\times4$ times $4\times2$, defined, size $3\times2$.
- $CB$: $4\times2$ times $3\times4$, not defined ($2\ne3$).
- $AC$: $2\times3$ times $4\times2$, not defined ($3\ne4$).
- $CA$: $4\times2$ times $2\times3$, defined, size $4\times3$.
- $AD$: $2\times3$ times $2\times2$, not defined ($3\ne2$).
- $DA$: $2\times2$ times $2\times3$, defined, size $2\times3$.

Every decision follows by checking the inner dimensions.
