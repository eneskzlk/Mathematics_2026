# Exercise 4 — Gauss–Jordan Elimination

## Question

Find $A^{-1}$ using the Gauss–Jordan method for

$$
A=
\begin{pmatrix}
1 & 2 \\
3 & 5 \\
\end{pmatrix}.
$$

Show the augmented matrix $[A\mid I]$ after successive operations and explain why obtaining $I$ on the left gives the inverse on the right.

## Solution

Start with

$$
[A\mid I]=\begin{pmatrix}
1 & 2 & \mid & 1 & 0 \\
3 & 5 & \mid & 0 & 1 \\
\end{pmatrix}.
$$

Apply $R_2\leftarrow R_2-3R_1$:

$$
\begin{pmatrix}
1 & 2 & \mid & 1 & 0 \\
0 & -1 & \mid & -3 & 1 \\
\end{pmatrix}.
$$

Apply $R_2\leftarrow-R_2$:

$$
\begin{pmatrix}
1 & 2 & \mid & 1 & 0 \\
0 & 1 & \mid & 3 & -1 \\
\end{pmatrix}.
$$

Apply $R_1\leftarrow R_1-2R_2$:

$$
\begin{pmatrix}
1 & 0 & \mid & -5 & 2 \\
0 & 1 & \mid & 3 & -1 \\
\end{pmatrix}.
$$

The right-hand block gives the inverse.

$$
A^{-1}=\begin{pmatrix}
-5&2 \\
3&-1 \\
\end{pmatrix}.
$$

Let $E$ be the product of the elementary matrices for the row operations. Applying these operations to $[A\mid I]$ gives $[EA\mid E]$. When $EA=I$, the right block $E$ is the inverse of the square matrix $A$.

Multiplication verifies the result.

$$
AA^{-1}=\begin{pmatrix}
-5+6 & 2-2 \\
-15+15 & 6-5 \\
\end{pmatrix}
=I_2.
$$
