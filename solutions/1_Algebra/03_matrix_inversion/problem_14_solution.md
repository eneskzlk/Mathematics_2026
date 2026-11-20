# Exercise 14 — A Self-Inverse Matrix

## Question

Assume that a square matrix $A$ satisfies

$$
A^2=I.
$$

Show that

$$
A^{-1}=A.
$$

Then give an example of a $2\times2$ matrix different from $I$ and $-I$ that satisfies this condition, and verify it by multiplication.

## Solution

Since $A^2=I$, multiplying $A$ by itself gives the identity on both sides. By the definition and uniqueness of the inverse, $A^{-1}=A$.

Take

$$
A=\begin{pmatrix}
0&1 \\
1&0 \\
\end{pmatrix},
$$

which is neither $I$ nor $-I$. Direct multiplication yields

$$
A^2=\begin{pmatrix}
0&1 \\
1&0 \\
\end{pmatrix}\begin{pmatrix}
0&1 \\
1&0 \\
\end{pmatrix}=\begin{pmatrix}
1&0 \\
0&1 \\
\end{pmatrix}.
$$

This transformation swaps the two coordinates twice, restoring the initial vector.
