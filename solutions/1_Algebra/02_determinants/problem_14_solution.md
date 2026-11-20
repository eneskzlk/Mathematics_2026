# Exercise 14 — Determinants

## Question

Consider the system $Ax=b$, where

$$
A=
\begin{pmatrix}
1 & 2 \\
k & 4 \\
\end{pmatrix}.
$$

For which values of $k$ does the system have exactly one solution for every $b$? For the remaining value, give an example of a right-hand side $b$ for which the system has infinitely many solutions, and an example for which it has no solution.

## Solution

The determinant of the coefficient matrix is

$$
\det A=1\cdot4-2k=4-2k.
$$

The system has one solution for every right-hand side exactly when $4-2k\ne0$, or $k\ne2$.

At $k=2$, the second equation has left-hand side twice the first: $2x+4y$ versus $x+2y$. If $b=(1,2)^T$, the equations are consistent and equivalent to $x+2y=1$, so infinitely many solutions exist (for example $y=t$, $x=1-2t$).

If instead $b=(1,0)^T$, the equations require simultaneously $x+2y=1$ and $2x+4y=0$, which is impossible because twice the first would be $2$, not $0$. Thus there is no solution.
