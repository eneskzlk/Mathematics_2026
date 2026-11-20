# Exercise 8 — Same Coefficient Matrix

## Question

Solve by elimination the two systems

$$
\begin{cases}
2x+y=5, \\
x-y=1,
\end{cases}
$$

$$
\begin{cases}
2x+y=1, \\
x-y=4.
\end{cases}
$$

Compare the successive elimination steps. Which part of the calculation is the same in both cases, and why?

## Solution

For $2x+y=5$, $x-y=1$, subtract twice equation 2 from equation 1 to get $3y=3$. Thus $y=1$, $x=2$.

For $2x+y=1$, $x-y=4$, the *same* elimination gives $3y=1-2(4)=-7$. Thus $y=-7/3$, $x=4+y=5/3$.

Checks: $2(2)+1=5$, $2-1=1$; $2(5/3)-7/3=1$, and $5/3-(-7/3)=4$.

In both systems the elimination multiplier and the resulting coefficient $3$ are identical: the coefficient matrix is the same. Only the transformed right-hand side changes.
