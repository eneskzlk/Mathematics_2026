# Exercise 12 — Determinants

Start with

$$
A(t)=\begin{pmatrix}
1&2&3 \\
2&4&t \\
0&1&1 \\
\end{pmatrix}.
$$

Apply $R_2\leftarrow R_2-2R_1$. Since this operation preserves the determinant,

$$
\det A(t)=
\det\begin{pmatrix}
1&2&3 \\
0&0&t-6 \\
0&1&1 \\
\end{pmatrix}
=-(t-6)=6-t.
$$

The determinant is zero exactly when $t=6$, so that is the sole noninvertible value. At $t=6$ the second row of the original matrix equals twice the first, which independently explains the singularity.
