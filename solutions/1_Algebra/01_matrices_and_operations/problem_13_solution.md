# Exercise 13 — Matrices and Basic Operations

## Question

Let

$$
F=
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix}.
$$

Compute $F^2$, $F^3$, $F^4$, and $F^5$. Compare the numbers obtained with the sequence

$$
0,1,1,2,3,5,8,\ldots
$$

and describe the relationship you observe. Then compute

$$
F
\begin{pmatrix}
a \\
b \\
\end{pmatrix}
$$

and explain how this multiplication performs one recurrence step: it creates the sum of two consecutive terms and keeps one of them for the next step.

## Solution

Direct matrix multiplication gives

$$
F^2=\begin{pmatrix}
2&1 \\
1&1 \\
\end{pmatrix},
\quad
F^3=\begin{pmatrix}
3&2 \\
2&1 \\
\end{pmatrix},
$$

$$
F^4=\begin{pmatrix}
5&3 \\
3&2 \\
\end{pmatrix},
\quad
F^5=\begin{pmatrix}
8&5 \\
5&3 \\
\end{pmatrix}.
$$

These contain the Fibonacci numbers $0,1,1,2,3,5,8,\ldots$, whose next term is the sum of its preceding two terms. For the ordinary Fibonacci sequence $f_0=0$, $f_1=1$:

$$
F^n=\begin{pmatrix}
f_{n+1}&f_n \\
f_n&f_{n-1} \\
\end{pmatrix}
\quad(n\ge1).
$$

For a state of two consecutive terms, multiplication performs one recurrence step:

$$
F\begin{pmatrix}
a \\
b \\
\end{pmatrix}
=\begin{pmatrix}
a+b \\
a \\
\end{pmatrix}.
$$

The newest sum is stored along with the previous first value, ready for the next step.
