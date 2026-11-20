# Exercise 12 — Matrices and Basic Operations

## Question

Let

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}.
$$

Compute $A^2$, $A^3$, and $A^4$, and use them to formulate a conjecture for $A^n$. Then do not stop after checking one more case: assume the formula is true for $n$, multiply by $A$, and explain why you obtain exactly the formula for $n+1$.

## Solution

Multiplying successive powers gives

$$
A^2=\begin{pmatrix}
1&2 \\
0&1 \\
\end{pmatrix},
\quad
A^3=\begin{pmatrix}
1&3 \\
0&1 \\
\end{pmatrix},
\quad
A^4=\begin{pmatrix}
1&4 \\
0&1 \\
\end{pmatrix}.
$$

Conjecture: for integers $n\ge1$,

$$
A^n=\begin{pmatrix}
1&n \\
0&1 \\
\end{pmatrix}.
$$

The case $n=1$ is true. If the formula holds for $n$, multiplication by $A$ yields

$$
A^{n+1}=
\begin{pmatrix}
1&n \\
0&1 \\
\end{pmatrix}
\begin{pmatrix}
1&1 \\
0&1 \\
\end{pmatrix}
=\begin{pmatrix}
1&n+1 \\
0&1 \\
\end{pmatrix}.
$$

The induction step proves the formula for every positive integer $n$.
