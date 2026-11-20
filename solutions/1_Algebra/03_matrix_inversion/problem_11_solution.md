# Exercise 11 — Parameter and Invertibility

$$A(t)=\begin{pmatrix}1&t\\t&1\end{pmatrix},\qquad\det A(t)=1-t^2.$$

For real $t$, the inverse exists exactly when $t\ne1$ and $t\ne-1$. In that case,

$$A(t)^{-1}=\frac1{1-t^2}\begin{pmatrix}1&-t\\-t&1\end{pmatrix}.$$

Multiplication gives $(1-t^2)I/(1-t^2)=I$. At $t=1$ the rows agree; at $t=-1$ they are negatives. In each case the determinant vanishes and the formula is undefined because the matrix is singular.