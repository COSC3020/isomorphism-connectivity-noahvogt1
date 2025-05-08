# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

PROOF:

$G_1 = (V_1, E_1)$, where $V_1 = {1, 2, 3}$ $E_1 = {(1,2)}$


$G_2 = (V_2, E_2)$, where $V_2 = {a, b, c}$ $E_2 = {(x,y)}$

We can define a bijective function $f : V_1 \rightarrow V_2$ such that: $f(1) = a$, $f(2) = b$, $f(3) = c$

We have to make sure the edges are the same: Because $(1,2) \in E_1$, we have $(f(1), f(2)) = (x,y) \in E_2$
Therefore, $G_1$ is isomorphic to $G_2$, but neither graph is completely connected.

This proves that isomorphic graphs do not need to be completely connected.
