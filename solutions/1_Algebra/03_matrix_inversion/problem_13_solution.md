# Exercise 13 — Undoing a Composite Transformation

$$T=HS=\begin{pmatrix}1&1\\0&1\end{pmatrix}\begin{pmatrix}2&0\\0&1\end{pmatrix}=\begin{pmatrix}2&1\\0&1\end{pmatrix}.$$

Its determinant is $2$, giving directly

$$T^{-1}=\begin{pmatrix}1/2&-1/2\\0&1\end{pmatrix}.$$

Alternatively, $S^{-1}=\operatorname{diag}(1/2,1)$ and $H^{-1}=\begin{pmatrix}1&-1\\0&1\end{pmatrix}$. Thus

$$S^{-1}H^{-1}=\begin{pmatrix}1/2&-1/2\\0&1\end{pmatrix}=T^{-1}.$$

The incorrect order produces

$$H^{-1}S^{-1}=\begin{pmatrix}1/2&-1\\0&1\end{pmatrix}\ne T^{-1}.$$

To undo a composition, undo the last operation first; indeed $T(S^{-1}H^{-1})=I$.