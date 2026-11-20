# Exercise 7 — Choosing a Method

## Question

Do not solve all of the following systems completely. For each situation, choose the method that best uses its structure and justify your choice:

1. one system with a triangular coefficient matrix

$$
\begin{cases}
2x-y=3, \\
4y=8;
\end{cases}
$$

2. three systems $Ax=b_i$ with the same invertible matrix $A$, when $A^{-1}$ is already known;
3. one $3\times3$ system for which the inverse matrix is not given and the goal is only to find one solution vector.

For case 1, carry out the chosen method completely. For cases 2 and 3, describe the plan and indicate which part of the computation would be reusable or unnecessary. Do not judge a method by its name alone — refer to the number of right-hand sides and the structure of the matrix.

## Solution

1. The coefficient matrix is triangular, so back-substitution is fastest. From $4y=8$, $y=2$; then $2x-y=3$ gives $x=5/2$. Check: $2(5/2)-2=3$.
2. With three right-hand sides and the same invertible $A$, use the already-known inverse: $x_i=A^{-1}b_i$ for $i=1,2,3$. Reuse $A^{-1}$; no need to eliminate the coefficient matrix repeatedly.
3. For a single $3\times3$ problem with no known inverse, Gaussian elimination on $[A\mid b]$ is generally preferable. Eliminate entries below pivots, then back-substitute; calculating all of $A^{-1}$ would be unnecessary work. The structure and number of right-hand sides determine the efficient method.
