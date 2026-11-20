## Question

Given

$$
A=(0,0,0),\qquad B=(1,2,0),\qquad C=(0,1,1),\qquad D=(2,5,1).
$$

1. Construct $\overrightarrow{AB}$ and $\overrightarrow{AC}$.
2. Find $n=\overrightarrow{AB}\times\overrightarrow{AC}$.
3. Construct $\overrightarrow{AD}$ and check whether $\overrightarrow{AD}\cdot n=0$.
4. Based on this, decide whether $D$ lies in the plane determined by $A,B,C$, and justify the criterion.

## Solution

The in-plane candidates are


$$
\overrightarrow{AB}=(1,2,0),\qquad \overrightarrow{AC}=(0,1,1).
$$



Their cross product is


$$
n=\overrightarrow{AB}\times\overrightarrow{AC}=(2,-1,1).
$$



Also $\overrightarrow{AD}=(2,5,1)$. I compute


$$
\overrightarrow{AD}\cdot n=2\cdot2+5(-1)+1\cdot1=4-5+1=0.
$$



Since $n\ne0$, the vectors $\overrightarrow{AB}$ and $\overrightarrow{AC}$ are independent. They span the two-dimensional space of vectors orthogonal to $n$. Therefore a point $D$ lies in the plane through $A,B,C$ exactly when $\overrightarrow{AD}\cdot n=0$. The computed zero confirms that the four points are coplanar.
