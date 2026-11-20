# Exercise 9 — Determinants

## Question

The vectors

$$
u=
\begin{pmatrix}
3 \\
1 \\
\end{pmatrix},\qquad v=
\begin{pmatrix}
1 \\
4 \\
\end{pmatrix}
$$

span a parallelogram. Compute its area using a determinant. Then reverse the order of the vectors and explain what changes in the determinant and what does not change in the area.

## Solution

The vectors $u=(3,1)^T$ and $v=(1,4)^T$ form columns of a $2\times2$ matrix. The parallelogram area is the absolute value of its determinant:

$$
\det\begin{pmatrix}
3&1 \\
1&4 \\
\end{pmatrix}
=3\cdot4-1\cdot1=11,
\qquad \mathrm{Area}=|11|=11.
$$

Reversing the column order produces

$$
\det\begin{pmatrix}
1&3 \\
4&1 \\
\end{pmatrix}
=1-12=-11.
$$

The sign changes because orientation changes, but the absolute value, and thus the geometric area, remains $11$.
