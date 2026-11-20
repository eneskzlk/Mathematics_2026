# Exercise 7 — Matrices and Basic Operations

## Question

For

$$
A=
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}
$$

compute

$$
AI,\qquad IA,\qquad A+0,\qquad A^2,\qquad A^3.
$$

Explain the roles of the matrices $I$ and $0$, and describe the pattern you observe in successive powers of $A$.

## Solution

The $2\times2$ identity matrix $I$ leaves any compatible matrix unchanged under multiplication; the zero matrix $0$ leaves it unchanged under addition:

$$
AI=IA=A+0=\begin{pmatrix}
2&1 \\
0&2 \\
\end{pmatrix}.
$$

Successive products are

$$
A^2=\begin{pmatrix}
4&4 \\
0&4 \\
\end{pmatrix},
\qquad
A^3=A^2A=\begin{pmatrix}
8&12 \\
0&8 \\
\end{pmatrix}.
$$

The pattern is

$$
A^n=\begin{pmatrix}
2^n&n\,2^{n-1} \\
0&2^n \\
\end{pmatrix}
\quad (n\ge1).
$$

Set $N=A-2I$. The only nonzero entry of $N$ is a $1$ in position $(1,2)$, so $N^2=0$. Since $2I$ commutes with $N$, the binomial expansion of $(2I+N)^n$ reduces to $2^nI+n2^{n-1}N$. Checking $n=2$ and $n=3$ reproduces the computed powers.
