# Exercise 5 — Gauss–Jordan for a 3×3 Matrix

## Question

Use Gauss–Jordan elimination to find the inverse of

$$
A=
\begin{pmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
\end{pmatrix}.
$$

Check the result by multiplication.

## Solution

$$
[A\mid I]=\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 1 & \mid & 0 & 1 & 0 \\
1 & 0 & 1 & \mid & 0 & 0 & 1 \\
\end{pmatrix}.
$$

After $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 1 & \mid & 0 & 1 & 0 \\
0 & -1 & 1 & \mid & -1 & 0 & 1 \\
\end{pmatrix}.
$$

After $R_3\leftarrow R_3+R_2$:

$$
\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 1 & \mid & 0 & 1 & 0 \\
0 & 0 & 2 & \mid & -1 & 1 & 1 \\
\end{pmatrix}.
$$

Divide $R_3$ by $2$, then use $R_2\leftarrow R_2-R_3$ and $R_1\leftarrow R_1-R_2$:

$$
\begin{pmatrix}
1 & 0 & 0 & \mid & 1/2 & -1/2 & 1/2 \\
0 & 1 & 0 & \mid & 1/2 & 1/2 & -1/2 \\
0 & 0 & 1 & \mid & -1/2 & 1/2 & 1/2 \\
\end{pmatrix}.
$$

Therefore

$$
A^{-1}=\frac12\begin{pmatrix}
1&-1&1 \\
1&1&-1 \\
-1&1&1 \\
\end{pmatrix}.
$$

Multiplication confirms $AA^{-1}=\frac12\mathrm{diag}(2,2,2)=I_3$.
