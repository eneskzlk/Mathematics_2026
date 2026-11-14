# Exercise 15 — Matrices and Basic Operations

First calculate

$$
AB=\begin{pmatrix}5&2\\1&4\\\end{pmatrix},
\qquad
(AB)C=\begin{pmatrix}10&3\\2&-3\\\end{pmatrix}.
$$

For the alternative grouping,

$$
BC=\begin{pmatrix}
2&1\\
4&1\\
-2&-4\\
\end{pmatrix},
\qquad
A(BC)=\begin{pmatrix}10&3\\2&-3\\\end{pmatrix}.
$$

Thus $(AB)C=A(BC)$, which illustrates associativity: changing parentheses does not change the product, provided the order of factors stays the same.

Using the ordinary row-column method, computing $AB$ takes $4\cdot3=12$ scalar multiplications and then $(AB)C$ takes $4\cdot2=8$, totaling $20$. Computing $BC$ takes $6\cdot2=12$ and $A(BC)$ takes $4\cdot3=12$, totaling $24$. So different parenthesizations can have different computational costs even with identical results.
