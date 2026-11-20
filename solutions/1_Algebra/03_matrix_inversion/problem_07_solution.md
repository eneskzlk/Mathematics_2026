# Exercise 7 — Inverse of a Product

## Question

For

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
2 & 0 \\
0 & 3 \\
\end{pmatrix}
$$

compute $(AB)^{-1}$ and $B^{-1}A^{-1}$. Check that the results are the same and explain the meaning of the reversed order.

## Solution

$$
AB=\begin{pmatrix}
2&3 \\
0&3 \\
\end{pmatrix},\quad (AB)^{-1}=\begin{pmatrix}
1/2&-1/2 \\
0&1/3 \\
\end{pmatrix}.
$$

Also

$$
A^{-1}=\begin{pmatrix}
1&-1 \\
0&1 \\
\end{pmatrix},\quad B^{-1}=\begin{pmatrix}
1/2&0 \\
0&1/3 \\
\end{pmatrix},
$$

so

$$
B^{-1}A^{-1}=\begin{pmatrix}
1/2&-1/2 \\
0&1/3 \\
\end{pmatrix}=(AB)^{-1}.
$$

Indeed $(AB)(B^{-1}A^{-1})=A(BB^{-1})A^{-1}=I$. To undo “apply $B$, then apply $A$,” undo $A$ first, then $B$.
