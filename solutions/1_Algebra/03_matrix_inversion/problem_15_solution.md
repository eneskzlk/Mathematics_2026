# Exercise 15 — Two Methods for One System

## Question

For

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
7 \\
8 \\
\end{pmatrix}
$$

solve $Ax=b$ in two ways:

1. using $A^{-1}b$,
2. using Gaussian elimination.

Compare both solutions, the number of essential steps, and state which method was simpler in this example.

## Solution

We solve $2x+y=7$ and $x+3y=8$.

**Inverse method.** Since $\det A=5$,

$$
A^{-1}=\frac15\begin{pmatrix}
3&-1 \\
-1&2 \\
\end{pmatrix},\quad A^{-1}b=\frac15\begin{pmatrix}
21-8 \\
-7+16 \\
\end{pmatrix}=\begin{pmatrix}
13/5 \\
9/5 \\
\end{pmatrix}.
$$

**Gaussian elimination.** From

$$
\begin{pmatrix}
2 & 1 & \mid & 7 \\
1 & 3 & \mid & 8 \\
\end{pmatrix}
$$

swap rows, then $R_2\leftarrow R_2-2R_1$ to obtain

$$
\begin{pmatrix}
1 & 3 & \mid & 8 \\
0 & -5 & \mid & -9 \\
\end{pmatrix}.
$$

Therefore $y=9/5$ and $x=8-3(9/5)=13/5$.

Both methods agree. Check: $2(13/5)+9/5=7$ and $13/5+3(9/5)=8$. Gaussian elimination needs one row swap, one elimination, and back-substitution; it is shorter for this one system, while an already-computed inverse is reusable for many right-hand sides.
