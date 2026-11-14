# Exercise 7 — Matrices and Basic Operations

The $2\times2$ identity matrix $I$ leaves any compatible matrix unchanged under multiplication; the zero matrix $0$ leaves it unchanged under addition:

$$
AI=IA=A+0=\begin{pmatrix}
2&1\\
0&2\\
\end{pmatrix}.
$$

Successive products are

$$
A^2=\begin{pmatrix}4&4\\0&4\\\end{pmatrix},
\qquad
A^3=A^2A=\begin{pmatrix}8&12\\0&8\\\end{pmatrix}.
$$

The pattern is

$$
A^n=\begin{pmatrix}2^n&n\,2^{n-1}\\0&2^n\\\end{pmatrix}
\quad (n\ge1).
$$

It holds because $A=2I+N$, $N^2=0$, so the binomial expansion leaves $2^nI+n2^{n-1}N$. Checking $n=2$ and $n=3$ reproduces the computed powers.
