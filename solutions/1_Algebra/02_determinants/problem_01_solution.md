# Exercise 1 — Determinants

## Question

Compute

$$
\det
\begin{pmatrix}
3 & -2 \\
5 & 4 \\
\end{pmatrix},\qquad \det
\begin{pmatrix}
1 & 7 \\
2 & 14 \\
\end{pmatrix}.
$$

Which matrix is invertible? Justify your answer.

## Solution

For a $2\times2$ matrix, the determinant is given by the following formula.

$$
\det\begin{pmatrix}
a&b \\
c&d \\
\end{pmatrix}=ad-bc.
$$

Applying the formula to both matrices gives the following values.

$$
\det\begin{pmatrix}
3&-2 \\
5&4 \\
\end{pmatrix}
=3(4)-(-2)(5)=22,
$$

and

$$
\det\begin{pmatrix}
1&7 \\
2&14 \\
\end{pmatrix}
=1(14)-7(2)=0.
$$

The first matrix is invertible because its determinant is nonzero. The second is not: its second row is twice its first, which independently confirms determinant zero.
