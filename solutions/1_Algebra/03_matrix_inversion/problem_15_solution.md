# Exercise 15 — Two Methods for One System

We solve $2x+y=7$ and $x+3y=8$.

**Inverse method.** Since $\det A=5$,

$$A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix},\quad A^{-1}b=\frac15\begin{pmatrix}21-8\\-7+16\end{pmatrix}=\begin{pmatrix}13/5\\9/5\end{pmatrix}.$$

**Gaussian elimination.** From

$$\left[\begin{array}{cc|c}2&1&7\\1&3&8\end{array}\right]$$

swap rows, then $R_2\leftarrow R_2-2R_1$ to obtain

$$\left[\begin{array}{cc|c}1&3&8\\0&-5&-9\end{array}\right].$$

Therefore $y=9/5$ and $x=8-3(9/5)=13/5$.

Both methods agree. Check: $2(13/5)+9/5=7$ and $13/5+3(9/5)=8$. Gaussian elimination needs one row swap, one elimination, and back-substitution; it is shorter for this one system, while an already-computed inverse is reusable for many right-hand sides.