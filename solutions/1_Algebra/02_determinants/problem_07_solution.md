# Exercise 7 — Determinants

## Question

Suppose that for a $3\times3$ matrix, $\det A=-4$. Compute

$$
\det(2A),\qquad \det(A^T),\qquad \det(A^2),\qquad \det(-A).
$$

Justify each answer using the appropriate property.

## Solution

For a $3\times3$ matrix and scalar $k$, $\det(kA)=k^3\det A$. Also, determinants are unchanged by transpose, multiplicative under products, and satisfy $\det(-A)=(-1)^3\det A$.

Given $\det A=-4$:

$$
\det(2A)=2^3(-4)=-32,
$$

$$
\det(A^T)=-4,\qquad \det(A^2)=(-4)^2=16,
$$

$$
\det(-A)=(-1)^3(-4)=4.
$$

The factor $k^3$ comes from multiplying each of the three rows by $k$.
