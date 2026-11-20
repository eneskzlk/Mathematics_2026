# Exercise 10 — Diagonal Matrices

## Question

Given

$$
D=
\begin{pmatrix}
2 & 0 & 0 \\
0 & -3 & 0 \\
0 & 0 & 5 \\
\end{pmatrix},\qquad E=
\begin{pmatrix}
2 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}.
$$

Without using Gauss–Jordan elimination, decide which matrix is invertible. For the invertible matrix, give the inverse and check the result by multiplication.

## Solution

$D=\mathrm{diag}(2,-3,5)$ is invertible since every diagonal entry is nonzero:

$$
D^{-1}=\mathrm{diag}(1/2,-1/3,1/5).
$$

Checking diagonal products gives $DD^{-1}=\mathrm{diag}(1,1,1)=I_3$. Matrix $E=\mathrm{diag}(2,0,5)$ is singular: its middle row is zero and $\det E=0$, so no inverse exists.
