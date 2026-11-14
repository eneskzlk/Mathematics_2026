# Exercise 6 — Matrices and Basic Operations

Transposition exchanges rows and columns:

$$
A^T=\begin{pmatrix}
1&4 \\
2&5 \\
3&6 \\
\end{pmatrix},
\qquad
B^T=\begin{pmatrix}
1&2&-1 \\
0&1&3 \\
\end{pmatrix}.
$$

Multiplying the original matrices gives

$$
AB=\begin{pmatrix}
1+4-3&0+2+9 \\
4+10-6&0+5+18 \\
\end{pmatrix}
=\begin{pmatrix}
2&11 \\
8&23 \\
\end{pmatrix}.
$$

Therefore

$$
(AB)^T=\begin{pmatrix}
2&8 \\
11&23 \\
\end{pmatrix}
=B^TA^T.
$$

The equality can also be verified by multiplying the displayed $B^T$ and $A^T$. Transposing a product reverses factor order.
