# Exercise 13 — Undoing a Composite Transformation

## Question

The matrices

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad H=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
$$

describe nonuniform scaling and shear. For $T=HS$, find $T^{-1}$ in two ways:

1. first compute $T$, then its inverse,
2. use $(HS)^{-1}=S^{-1}H^{-1}$.

Compare the results. Additionally compute $H^{-1}S^{-1}$ and verify that the incorrect order gives a different matrix. Explain the rule: “when undoing a composition of operations, we undo them from the end.”

## Solution

$$
T=HS=\begin{pmatrix}
1&1 \\
0&1 \\
\end{pmatrix}\begin{pmatrix}
2&0 \\
0&1 \\
\end{pmatrix}=\begin{pmatrix}
2&1 \\
0&1 \\
\end{pmatrix}.
$$

Its determinant is $2$, giving directly

$$
T^{-1}=\begin{pmatrix}
1/2&-1/2 \\
0&1 \\
\end{pmatrix}.
$$

Alternatively, compute the individual inverses.

$$
S^{-1}=\mathrm{diag}(1/2,1),\qquad H^{-1}=\begin{pmatrix}
1&-1 \\
0&1 \\
\end{pmatrix}.
$$

Multiplying in reverse order gives

$$
S^{-1}H^{-1}=\begin{pmatrix}
1/2&-1/2 \\
0&1 \\
\end{pmatrix}=T^{-1}.
$$

The incorrect order produces

$$
H^{-1}S^{-1}=\begin{pmatrix}
1/2&-1 \\
0&1 \\
\end{pmatrix}\ne T^{-1}.
$$

To undo a composition, undo the last operation first; indeed $T(S^{-1}H^{-1})=I$.
