# Exercise 15 — Matrices and Basic Operations

## Question

Given

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\quad B=
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix},\quad C=
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix}.
$$

Compute $(AB)C$ and $A(BC)$. Compare the results and the number of intermediate operations. Explain what associativity of matrix multiplication means in this example.

## Solution

First calculate

$$
AB=\begin{pmatrix}
5&2 \\
1&4 \\
\end{pmatrix},
\qquad
(AB)C=\begin{pmatrix}
10&3 \\
2&-3 \\
\end{pmatrix}.
$$

For the alternative grouping,

$$
BC=\begin{pmatrix}
2&1 \\
4&1 \\
-2&-4 \\
\end{pmatrix},
\qquad
A(BC)=\begin{pmatrix}
10&3 \\
2&-3 \\
\end{pmatrix}.
$$

Thus $(AB)C=A(BC)$, which illustrates associativity: changing parentheses does not change the product, provided the order of factors stays the same.

In the ordinary row–column method, each output entry is a dot product of length $k$ and takes $k$ scalar multiplications and $k-1$ additions. Counting every entry gives the following costs.

| Product | Multiplications | Additions |
| --- | ---: | ---: |
| $AB$ | 12 | 8 |
| $(AB)C$ | 8 | 4 |
| **Total for $(AB)C$** | **20** | **12** |
| $BC$ | 12 | 6 |
| $A(BC)$ | 12 | 8 |
| **Total for $A(BC)$** | **24** | **14** |

Thus $(AB)C$ uses $32$ scalar operations and $A(BC)$ uses $38$ by this counting convention.
