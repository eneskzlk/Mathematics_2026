# Exercise 1 — Writing $Ax=b$

## Question

Write the system

$$
\begin{cases}
2x-y+z=4, \\
x+3y-2z=1, \\
3x+y+z=7.
\end{cases}
$$

in the form $Ax=b$.
Identify the coefficient matrix, the vector of unknowns, and the right-hand side vector. Explain how each row of the matrix corresponds to one equation.

## Solution

The coefficient matrix, unknown vector, and right-hand side are

$$
A=\begin{pmatrix}
2&-1&1 \\
1&3&-2 \\
3&1&1 \\
\end{pmatrix},\qquad x=\begin{pmatrix}
x \\
y \\
z \\
\end{pmatrix},\qquad b=\begin{pmatrix}
4 \\
1 \\
7 \\
\end{pmatrix}.
$$

Thus the system is $Ax=b$. Each row is exactly the coefficients of one original equation, in the order $x,y,z$. For example, row 2 produces $x+3y-2z=1$.
