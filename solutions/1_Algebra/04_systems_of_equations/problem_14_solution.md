# Exercise 14 — Changed Right-Hand Side

## Question

Compare the systems

$$
\begin{cases}
x+y=2, \\
2x-y=1, \\
3x=3
\end{cases}
$$

and

$$
\begin{cases}
x+y=2, \\
2x-y=1, \\
3x=3.1.
\end{cases}
$$

Check the consistency of each system and explain why a small change in one number can change the type of the system.

## Solution

For both systems, the first two equations are

$$
x+y=2,\qquad 2x-y=1.
$$

Adding yields $3x=3$, hence $x=1$ and $y=1$.

**First system:** the third equation $3x=3$ holds, so there is one solution, $(1,1)$.

**Second system:** the third equation demands $3x=3.1$, but the first two force $3x=3$. Thus it is inconsistent and has no solutions.

The third equation is redundant in the first system but contradictory in the second. Even a $0.1$ perturbation can cause inconsistency when the system imposes an exact additional constraint.
