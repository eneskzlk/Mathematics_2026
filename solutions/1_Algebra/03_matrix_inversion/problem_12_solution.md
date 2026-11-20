# Exercise 12 — Inverse Properties

## Question

It is known that

$$
A^{-1}=
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}.
$$

Without finding $A$, compute $(3A)^{-1}$, $(A^T)^{-1}$, and $(A^2)^{-1}$. Justify each result using the appropriate property.

## Solution

The scalar, transpose, and product rules give the following three inverses.

$$
(3A)^{-1}=\frac13A^{-1}=\begin{pmatrix}
2/3&-1/3 \\
-1&2/3 \\
\end{pmatrix}.
$$

$$
(A^T)^{-1}=(A^{-1})^T=\begin{pmatrix}
2&-3 \\
-1&2 \\
\end{pmatrix}.
$$

$$
(A^2)^{-1}=(A^{-1})^2=\begin{pmatrix}
7&-4 \\
-12&7 \\
\end{pmatrix}.
$$

These follow from $(cA)(c^{-1}A^{-1})=I$, transposing $AA^{-1}=I$, and $A^2(A^{-1})^2=I$.
