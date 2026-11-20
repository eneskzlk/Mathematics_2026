# Exercise 6 — Solving with the Inverse

## Question

Solve

$$
Ax=b,
$$

where

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix},
$$

using $x=A^{-1}b$. Then substitute the resulting vector back into the equation and check the result.

## Solution

$$
A^{-1}=\frac1{2\cdot3-1}\begin{pmatrix}
3&-1 \\
-1&2 \\
\end{pmatrix}=\frac15\begin{pmatrix}
3&-1 \\
-1&2 \\
\end{pmatrix}.
$$

Hence

$$
x=A^{-1}b=\frac15\begin{pmatrix}
15-7 \\
-5+14 \\
\end{pmatrix}=\begin{pmatrix}
8/5 \\
9/5 \\
\end{pmatrix}.
$$

Check: $2(8/5)+9/5=5$ and $8/5+3(9/5)=7$, so $Ax=b$.
