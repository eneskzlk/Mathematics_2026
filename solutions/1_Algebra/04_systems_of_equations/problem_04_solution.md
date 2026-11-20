# Exercise 4 — Infinitely Many Solutions

## Question

Solve

$$
\begin{cases}
x+y+z=2, \\
2x+2y+2z=4, \\
x-y+z=0.
\end{cases}
$$

Give the solution in parametric form, identify a free variable, and for one chosen parameter value check that the resulting point really satisfies the system.

## Solution

Equation 2 is twice equation 1, so it is redundant. Subtracting equation 3 from equation 1 gives $2y=2$, hence $y=1$. Equation 1 now gives $x+z=1$.

Let $z=t\in\mathbb R$. All solutions are

$$
(x,y,z)=(1-t,1,t),\quad t\in\mathbb R.
$$

For example, $t=0$ gives $(1,1,0)$. Substitution produces $2$, $4$, and $0$ on the three left sides, matching their right sides.
