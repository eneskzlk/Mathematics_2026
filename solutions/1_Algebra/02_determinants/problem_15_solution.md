# Exercise 15 — Determinants

## Question

Let $A$ and $B$ be invertible $2\times2$ matrices with

$$
\det A=-2,\qquad \det B=3.
$$

Without finding the entries of the matrices, compute

$$
\det\left(B^{-1}A^TB\right).
$$

State the determinant properties you use in order and explain why the factors involving $B$ eventually cancel.

## Solution

Use multiplicativity, the inverse rule, and invariance under transpose:

$$
\det(B^{-1}A^TB)
=\det(B^{-1})\det(A^T)\det(B).
$$

Since $\det B=3$, $\det(B^{-1})=1/3$. Also $\det(A^T)=\det A=-2$. Therefore

$$
\det(B^{-1}A^TB)
=\frac13(-2)(3)=-2.
$$

The determinants of $B^{-1}$ and $B$ multiply to $1$. This is why the two factors involving $B$ cancel.
