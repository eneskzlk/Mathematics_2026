## Question

Decompose $u=(3,4)$ into components parallel and perpendicular to $v=(1,2)$. Check

$$
u=u_{\parallel}+u_{\perp},\qquad u_{\perp}\cdot v=0.
$$

Explain why these are two independent checks of correctness.

## Solution

The parallel component is the projection:


$$
u_{\parallel}=\frac{u\cdot v}{v\cdot v}v=\frac{11}{5}(1,2)=\left(\frac{11}{5},\frac{22}{5}\right).
$$



Subtracting it from $u$ gives


$$
u_{\perp}=u-u_{\parallel}=\left(\frac45,-\frac25\right).
$$



The reconstruction check is


$$
u_{\parallel}+u_{\perp}=\left(\frac{15}{5},\frac{20}{5}\right)=(3,4)=u,
$$



while the orthogonality check is


$$
u_{\perp}\cdot v=\frac45-\frac45=0.
$$



The computed $u_{\parallel}$ is a scalar multiple of $v$. Even with that restriction, the two checks test different properties. Taking the candidate pair $(0,u)$ satisfies reconstruction but fails the dot-product check because $u\cdot v=11$. Taking the candidate pair $(0,0)$ passes the dot-product check but fails reconstruction because $u\ne0$.
