# Exercise 10 — Matrices and Basic Operations

The two columns of $B$ are $b_1=(1,-1,3)^T$ and $b_2=(2,0,1)^T$. Matrix-vector multiplication gives

$$
Ab_1=\begin{pmatrix}
1(1)+2(-1)+0(3)\\
0(1)+1(-1)+1(3)\\
\end{pmatrix}
=\begin{pmatrix}-1\\2\\\end{pmatrix},
$$

and

$$
Ab_2=\begin{pmatrix}
1(2)+2(0)+0(1)\\
0(2)+1(0)+1(1)\\
\end{pmatrix}
=\begin{pmatrix}2\\1\\\end{pmatrix}.
$$

Hence

$$
AB=\begin{pmatrix}-1&2\\2&1\\\end{pmatrix}
=\begin{pmatrix}Ab_1&Ab_2\end{pmatrix}.
$$

The $j$-th column of a matrix product is the first matrix applied to the $j$-th column of the second.
