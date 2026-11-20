# Exercise 2 — Inverse of a 2×2 Matrix

## Question

Find the inverse of

$$
A=
\begin{pmatrix}
3 & 2 \\
5 & 4 \\
\end{pmatrix}
$$

using the formula for a $2\times2$ matrix. At the end, check the result by computing one product with $A$.

## Solution

$$
\det A=3\cdot4-2\cdot5=2\ne0.
$$

The inverse formula yields

$$
A^{-1}=\frac1{2}\begin{pmatrix}
4&-2 \\
-5&3 \\
\end{pmatrix}=\begin{pmatrix}
2&-1 \\
-5/2&3/2 \\
\end{pmatrix}.
$$

Verification:

$$
AA^{-1}=\frac12\begin{pmatrix}
12-10&-6+6 \\
20-20&-10+12 \\
\end{pmatrix}=I_2.
$$
