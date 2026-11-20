# Exercise 2 — Gaussian Elimination

Starting from

$$\left[\begin{array}{ccc|c}1&1&1&6\\2&-1&1&3\\1&2&-1&2\end{array}\right],$$

use $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$:

$$\left[\begin{array}{ccc|c}1&1&1&6\\0&-3&-1&-9\\0&1&-2&-4\end{array}\right].$$

Swap $R_2,R_3$, then $R_3\leftarrow R_3+3R_2$:

$$\left[\begin{array}{ccc|c}1&1&1&6\\0&1&-2&-4\\0&0&-7&-21\end{array}\right].$$

Back-substitute: $z=3$, $y-2(3)=-4\Rightarrow y=2$, $x+2+3=6\Rightarrow x=1$.

Check: $1+2+3=6$, $2-2+3=3$, and $1+4-3=2$. Hence $(x,y,z)=(1,2,3)$.