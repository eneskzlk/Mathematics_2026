# Exercise 11 — Matrices and Basic Operations

Direct multiplication gives

$$
AB=\begin{pmatrix}
a+c&b+d \\
c&d \\
\end{pmatrix},
\qquad
BA=\begin{pmatrix}
a&a+b \\
c&c+d \\
\end{pmatrix}.
$$

Equating corresponding entries gives $a+c=a$ and $b+d=a+b$, so $c=0$ and $d=a$. The other two equalities are then automatic.

Thus all commuting matrices have the form

$$
B=\begin{pmatrix}
a&b \\
0&a \\
\end{pmatrix},
$$

where $a,b$ may be arbitrary. Substituting this form into both products verifies the equality.
