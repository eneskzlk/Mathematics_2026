# Exercise 1 — Definition of the Inverse

## Question

For

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & -1 \\
-1 & 2 \\
\end{pmatrix}
$$

check, without using a formula, whether $B=A^{-1}$. Compute $AB$ and $BA$ and relate the result to the definition of the inverse.

## Solution

Compute the two products to check the definition of an inverse.

$$
AB=\begin{pmatrix}
2-1&-2+2 \\
1-1&-1+2 \\
\end{pmatrix}=\begin{pmatrix}
1&0 \\
0&1 \\
\end{pmatrix}.
$$

Similarly,

$$
BA=\begin{pmatrix}
2-1&1-1 \\
-2+2&-1+2 \\
\end{pmatrix}=I_2.
$$

Thus both inverse identities hold, so $B=A^{-1}$.
