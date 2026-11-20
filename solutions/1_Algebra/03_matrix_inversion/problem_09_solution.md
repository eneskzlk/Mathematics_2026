# Exercise 9 — Matrix Equation $AX=B$

## Question

Given

$$
A=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix}.
$$

Solve the equation $AX=B$ for $X$. Before calculating, decide on which side of the equation $A^{-1}$ must be used. Then check the result by computing $AX$.

## Solution

Multiply $AX=B$ on the **left** by $A^{-1}$: $X=A^{-1}B$. Since

$$
A^{-1}=\begin{pmatrix}
1&-2 \\
0&1 \\
\end{pmatrix},
$$

we get

$$
X=\begin{pmatrix}
1&-2 \\
0&1 \\
\end{pmatrix}\begin{pmatrix}
3&1 \\
2&4 \\
\end{pmatrix}=\begin{pmatrix}
-1&-7 \\
2&4 \\
\end{pmatrix}.
$$

Verification:

$$
AX=\begin{pmatrix}
1&2 \\
0&1 \\
\end{pmatrix}\begin{pmatrix}
-1&-7 \\
2&4 \\
\end{pmatrix}=\begin{pmatrix}
3&1 \\
2&4 \\
\end{pmatrix}=B.
$$

Multiplication order cannot be arbitrarily reversed.
