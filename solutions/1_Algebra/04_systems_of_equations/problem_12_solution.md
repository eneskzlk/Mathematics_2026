# Exercise 12 — Homogeneous System

## Question

Solve

$$
\begin{cases}
x+2y-z=0, \\
2x+4y-2z=0, \\
x-y+2z=0.
\end{cases}
$$

Give all solutions in parametric form and explain why $(0,0,0)$ always satisfies a homogeneous system.

## Solution

Equation 2 is twice equation 1, so retain equations 1 and 3:

$$
x+2y-z=0,\qquad x-y+2z=0.
$$

Subtract the second from the first: $3y-3z=0$, hence $y=z$. Substitution gives $x=-z$. Put $z=t$:

$$
(x,y,z)=(-t,t,t),\qquad t\in\mathbb R.
$$

Both independent equations vanish on substitution, and equation 2 does too. A homogeneous system always admits $(0,0,0)$ because multiplying any coefficient matrix by the zero vector gives the zero vector.
