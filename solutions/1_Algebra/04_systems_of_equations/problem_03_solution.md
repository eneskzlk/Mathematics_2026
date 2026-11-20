# Exercise 3 — Inconsistent System

## Question

Solve or show that the system is inconsistent:

$$
\begin{cases}
x+2y=3, \\
2x+4y=7.
\end{cases}
$$

Show how the contradiction appears in the matrix after elimination and interpret it in terms of equations.

## Solution

The augmented matrix is

$$
\begin{pmatrix}
1 & 2 & \mid & 3 \\
2 & 4 & \mid & 7 \\
\end{pmatrix}.
$$

Subtract twice row 1 from row 2:

$$
\begin{pmatrix}
1 & 2 & \mid & 3 \\
0 & 0 & \mid & 1 \\
\end{pmatrix}.
$$

The last row says $0x+0y=1$, or $0=1$, a contradiction. Equivalently, doubling $x+2y=3$ gives $2x+4y=6$, not $7$. There is **no solution**.
