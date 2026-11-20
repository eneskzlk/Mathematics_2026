# Exercise 7 — Choosing a Method

1. The coefficient matrix is triangular, so back-substitution is fastest. From $4y=8$, $y=2$; then $2x-y=3$ gives $x=5/2$. Check: $2(5/2)-2=3$.
2. With three right-hand sides and the same invertible $A$, use the already-known inverse: $x_i=A^{-1}b_i$ for $i=1,2,3$. Reuse $A^{-1}$; no need to eliminate the coefficient matrix repeatedly.
3. For a single $3\times3$ problem with no known inverse, Gaussian elimination on $[A\mid b]$ is generally preferable. Eliminate entries below pivots, then back-substitute; calculating all of $A^{-1}$ would be unnecessary work. The structure and number of right-hand sides determine the efficient method.