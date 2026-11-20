# Exercise 11 — Parameter in Three Equations

## Question

Analyze the number of solutions depending on $t$:

$$
\begin{cases}
x+y+z=1, \\
x+ty+z=2, \\
x+y+tz=3.
\end{cases}
$$

Use elimination and separately analyze the parameter values for which a standard calculation step ceases to be valid.

## Solution

Subtract equation 1 from equations 2 and 3:

$$
(t-1)y=1,\qquad(t-1)z=2,\qquad x+y+z=1.
$$

For $t\ne1$ we can divide, giving

$$
y=\frac1{t-1},\qquad z=\frac2{t-1},\qquad x=1-\frac3{t-1}=\frac{t-4}{t-1}.
$$

So there is exactly one solution for every $t\ne1$. The determinant of the coefficient matrix is $(t-1)^2\ne0$.

At $t=1$, the first and second equations have identical left sides but different right sides ($1$ versus $2$). Thus the system is inconsistent, with **no solution**. There is no parameter value giving infinitely many solutions.
