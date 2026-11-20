# Exercise 8 — Inverting a Scaling

## Question

The matrix

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & \frac12 \\
\end{pmatrix}
$$

describes a scaling of the plane. Find $S^{-1}$ and explain geometrically what the inverse transformation does. Check the action of the pair $S,S^{-1}$ on one simple vector.

## Solution

$$
S=\mathrm{diag}(2,1/2),\qquad S^{-1}=\mathrm{diag}(1/2,2).
$$

The original map doubles horizontal coordinates and halves vertical ones; the inverse halves horizontal and doubles vertical coordinates. For $v=(2,4)^T$,

$$
Sv=(4,2)^T,\qquad S^{-1}Sv=(2,4)^T=v.
$$

Thus $S^{-1}S=I_2$.
