#point-set_topology

# Point-Set Topology

---

Topology allows us to make concepts like limits and continuity be much more rigorous rather than the solely intuitive notions we previously held.

Given a set $X$, $\tau \in P(X)$ is a topology on $X$ if $\emptyset, X \in \tau$ and $\tau$ only contains open sets, and if:

- $A, B \in \tau \implies A \cup B \in \tau$
- $A, B \in \tau \implies A \cap B \in \tau$
- finite and infinite unions are open sets in $\tau$
- finite intersections are open sets in $\tau$
- infinite intersections aren't necessarily open sets in $\tau$

$(X, \tau)$ a topological space.

Sets in $P(X)$ can either be:

- open
- closed
- both
- neither

$S \in X$ is open if $S \in \tau$, $S \in X$ is closed if $X - S \in \tau$.

Trivial topology: $X$ is any set; $\tau = \{\emptyset, X\}$.
$X$ is any set; $\tau = P(X)$

Any subset of $X$ is open if it's the union of an infinite amount of open balls, *or* any subset of $X$ is open if every point inside it has an open ball around it.

Metric space $X$ is Hausdorff if $\forall x', x'' \in X, \exists \epsilon', \epsilon'' > 0, B_{\epsilon'}(x') \cup B_{\epsilon''}(x'') = \emptyset$ in other words given any two elements in $X$, you can make two disjoint open balls around them. Every metric space is Hausdorff.

We can induce topologies on the set which has a metric on it, and those topologies are always Hausdorff. Not *every* topology on the set is Hausdorff however (find how to induce).

Topology is Hausdorff if from any two points we can find disjoint, open sets.

Given $(X, \tau)$, $\tau = \{\emptyset, X\}$, $\tau$ is not Hausdorff because no two elements $x', x'' \in X$ will be in disjoint open sets in $\tau$.

$T_0, T_1, T_2, T_3, T_4$ are degrees of separation, and they are invariant under homeomorphisms.

If $(X, \tau_X)$ and $(Y, \tau_Y)$ are topological spaces, we say $F:X$ -> $Y$ is continuous iff $\forall \gamma \in \tau_Y$, the primage of $\gamma$ is an element of $\tau_X$.

In other words, the preimage of every set in $\tau_Y$ (every open set in the topology) must be open for it to be continuous.

Example: $(X, \tau)$, $X =\{1, 2, \pi\}$, $\tau = \{\emptyset, \{1\}, \{1, 2, \pi\}\}$. $F:$
- 1 -> 2
- 2 -> 1
- $\pi$ -> $\pi$

This is not continuous because the preimage of {1} (which is {2}) is not in $\tau_X$.

Another example: $(X, \tau_X)$ -> $(X, \tau_X)$ is trivially continuous.

Another example: $(X, \tau_X)$ -> $(Y, \tau_Y)$; $\exists a \in Y$; $F: \forall x\in X$ -> $a$. 

![[Pasted image 20210323132125.png]]

For any open set in $Y$ which doesn't contain $a$, the preimage is the null set. For any open set in $Y$ which does contain $a$, the preimage is the whole set $X$ unioned with the null set (so just the set $X$). Because $\tau_X$ must by definition contain $X$ and $\emptyset$, this mapping must be continuous, because all preimages are open sets in $\tau_X$.

A continuous function from $(X, \tau_X)$ -> $(Y, \tau_Y)$ is a homeomorphism if and only if the function is a bijection and has a continuous inverse. A homeomorphism is an equivalence relation.

---