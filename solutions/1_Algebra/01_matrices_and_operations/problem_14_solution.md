# Exercise 14 — Matrices and Basic Operations

Multiplying the two rotation matrices gives

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos\alpha\cos\beta-\sin\alpha\sin\beta &
-\cos\alpha\sin\beta-\sin\alpha\cos\beta \\
\sin\alpha\cos\beta+\cos\alpha\sin\beta &
-\sin\alpha\sin\beta+\cos\alpha\cos\beta \\
\end{pmatrix}.
$$

By the angle-addition identities, the entries become

$$
\begin{pmatrix}
\cos(\alpha+\beta)&-\sin(\alpha+\beta) \\
\sin(\alpha+\beta)&\cos(\alpha+\beta) \\
\end{pmatrix}
=R(\alpha+\beta).
$$

Geometrically, rotating by $\beta$ and then by $\alpha$ gives a net counterclockwise rotation by $\alpha+\beta$ (with signed angles).
