# Exercise 4 — Gauss–Jordan Elimination

Start with

$$[A\mid I]=\left[\begin{array}{cc|cc}1&2&1&0\\3&5&0&1\end{array}\right].$$

Apply $R_2\leftarrow R_2-3R_1$:

$$\left[\begin{array}{cc|cc}1&2&1&0\\0&-1&-3&1\end{array}\right].$$

Apply $R_2\leftarrow-R_2$:

$$\left[\begin{array}{cc|cc}1&2&1&0\\0&1&3&-1\end{array}\right].$$

Apply $R_1\leftarrow R_1-2R_2$:

$$\left[\begin{array}{cc|cc}1&0&-5&2\\0&1&3&-1\end{array}\right].$$

Thus $A^{-1}=\begin{pmatrix}-5&2\\3&-1\end{pmatrix}$. Each row operation multiplies both halves by the same elementary matrix. Once the left half becomes $I$, the right half is $A^{-1}$. Direct check: $AA^{-1}=I_2$.