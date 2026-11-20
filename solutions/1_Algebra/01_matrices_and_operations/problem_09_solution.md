# Exercise 9 — Matrices and Basic Operations

## Question

Let

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad R=
\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix}.
$$

The matrix $S$ describes nonuniform scaling, while $R$ describes a $90^\circ$ counterclockwise rotation.
For

$$
x=
\begin{pmatrix}
1 \\
2 \\
\end{pmatrix}
$$

compute $RSx$ and $SRx$. Compare the results and explain geometrically why the order of these transformations matters.

## Solution

Scale first:

$$
Sx=\begin{pmatrix}
2 \\
2 \\
\end{pmatrix},
\qquad
RSx=R(Sx)=\begin{pmatrix}
-2 \\
2 \\
\end{pmatrix}.
$$

Rotate first:

$$
Rx=\begin{pmatrix}
-2 \\
1 \\
\end{pmatrix},
\qquad
SRx=S(Rx)=\begin{pmatrix}
-4 \\
1 \\
\end{pmatrix}.
$$

The results differ: $(-2,2)^T\ne(-4,1)^T$. A nonuniform scaling emphasizes the original horizontal axis; rotating before rather than after scaling changes which geometric direction receives that enlargement.
