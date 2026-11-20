# Exercise 10 — Matrices and Basic Operations

## Question

Given

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & 2 \\
-1 & 0 \\
3 & 1 \\
\end{pmatrix}.
$$

Denote the columns of $B$ by $b_1,b_2$.

1. Compute $Ab_1$ and $Ab_2$.
2. Compute the matrix $AB$.
3. Compare the results and explain why the columns of $AB$ are exactly the vectors $Ab_1$ and $Ab_2$.

## Solution

The two columns of $B$ are $b_1=(1,-1,3)^T$ and $b_2=(2,0,1)^T$. Matrix-vector multiplication gives

$$
Ab_1=\begin{pmatrix}
1(1)+2(-1)+0(3) \\
0(1)+1(-1)+1(3) \\
\end{pmatrix}
=\begin{pmatrix}
-1 \\
2 \\
\end{pmatrix},
$$

and

$$
Ab_2=\begin{pmatrix}
1(2)+2(0)+0(1) \\
0(2)+1(0)+1(1) \\
\end{pmatrix}
=\begin{pmatrix}
2 \\
1 \\
\end{pmatrix}.
$$

Computing $AB$ directly by taking row–column dot products yields

$$
AB=\begin{pmatrix}
1-2+0 & 2+0+0 \\
0-1+3 & 0+0+1 \\
\end{pmatrix}
=\begin{pmatrix}
-1 & 2 \\
2 & 1 \\
\end{pmatrix}.
$$

Its columns agree with $Ab_1$ and $Ab_2$. Each entry in column $j$ of $AB$ is the corresponding row of $A$ dotted with $b_j$. Those same dot products form $Ab_j$.
