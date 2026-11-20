# Exercise 14 — A Self-Inverse Matrix

If $A^2=I$, then $AA=A^2=I$ and $AA=I$, so by the definition and uniqueness of the inverse, $A^{-1}=A$.

Take

$$A=\begin{pmatrix}0&1\\1&0\end{pmatrix},$$

which is neither $I$ nor $-I$. Direct multiplication yields

$$A^2=\begin{pmatrix}0&1\\1&0\end{pmatrix}\begin{pmatrix}0&1\\1&0\end{pmatrix}=\begin{pmatrix}1&0\\0&1\end{pmatrix}.$$

This transformation swaps the two coordinates twice, restoring the initial vector.