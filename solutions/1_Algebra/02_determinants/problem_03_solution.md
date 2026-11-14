# Exercise 3 — Determinants

Expanding the determinant of $A$ along the first row gives

$$
\det A=1(3\cdot1-1\cdot1)-2(0\cdot1-1\cdot2)=2+4=6.
$$

Swapping the first two rows changes the sign of a determinant, so the predicted value is $\det B=-6$.

To verify directly, the swapped matrix is

$$
B=\begin{pmatrix}
0&3&1\\
1&2&0\\
2&1&1\\
\end{pmatrix}.
$$

Expansion along the first row gives

$$
\det B=0-3(1\cdot1-0\cdot2)+1(1\cdot1-2\cdot2)=-3-3=-6.
$$

The calculation confirms the sign-change rule.
