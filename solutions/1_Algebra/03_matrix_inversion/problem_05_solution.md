# Exercise 5 — Gauss–Jordan for a 3×3 Matrix

$$[A\mid I]=\left[\begin{array}{ccc|ccc}1&1&0&1&0&0\\0&1&1&0&1&0\\1&0&1&0&0&1\end{array}\right].$$

After $R_3\leftarrow R_3-R_1$:

$$\left[\begin{array}{ccc|ccc}1&1&0&1&0&0\\0&1&1&0&1&0\\0&-1&1&-1&0&1\end{array}\right].$$

After $R_3\leftarrow R_3+R_2$:

$$\left[\begin{array}{ccc|ccc}1&1&0&1&0&0\\0&1&1&0&1&0\\0&0&2&-1&1&1\end{array}\right].$$

Divide $R_3$ by $2$, then use $R_2\leftarrow R_2-R_3$ and $R_1\leftarrow R_1-R_2$:

$$\left[\begin{array}{ccc|ccc}1&0&0&1/2&-1/2&1/2\\0&1&0&1/2&1/2&-1/2\\0&0&1&-1/2&1/2&1/2\end{array}\right].$$

Therefore

$$A^{-1}=\frac12\begin{pmatrix}1&-1&1\\1&1&-1\\-1&1&1\end{pmatrix}.$$

Multiplication confirms $AA^{-1}=\frac12\operatorname{diag}(2,2,2)=I_3$.