# Exercise 6 — Determinants

## Question

For

$$
A(t)=
\begin{pmatrix}
t & 1 \\
2 & t \\
\end{pmatrix}
$$

find all values of $t$ for which the matrix is not invertible. Explain how your answer is related to the determinant being zero.

## Solution

A square matrix is noninvertible exactly when its determinant is zero:

$$
\det A(t)=\det\begin{pmatrix}
t&1 \\
2&t \\
\end{pmatrix}
=t^2-2.
$$

Thus

$$
t^2-2=0\quad\Longleftrightarrow\quad t=\sqrt2
\quad\mathrm{or}\quad t=-\sqrt2.
$$

For all other real $t$, $\det A(t)\ne0$ and the inverse exists. Substituting either exceptional value makes $t^2-2=0$, verifying the answer.
