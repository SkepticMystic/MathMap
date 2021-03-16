#set_theory 

# Proper Subsets and Proper Supersets

---

Say we have two sets: $A$ and $B$:

<html>
	<center>
		<svg width="400" height="400">
			<circle cx="200" cy="200" r="190" stroke="red" stroke-width="4" fill="none"/>
			<circle cx="230" cy="230" r="80" stroke="blue" stroke-width="4" fill="none"/>
			
			<text x="55" y="55" fill="red">B</text>
			<text x="160" y="160" fill="blue">A</text>
		</svg>
	</center>
</html>

We would say that $A$ is a **proper subset** of $B$ if both of the following are true:

- $A$ is a subset of $B$
- $A$ is not equal to $B$

This is different from the normal subset in that if $A$ is a normal subset of $B$, $A$ could be equal to $B$.

We already know that if $A$ is a subset of $B$, $B$ is a superset of $A$. Similarly, if $A$ is a proper subset of $B$, $B$ will be a proper superset of $A$. In other words, $B$ will be a **proper superset** of $A$ if:

- $B$ is a superset of $A$
- $B$ is not equal to $A$

Looking at our Euler diagram, hopefully it's clear that for $A$ to be a proper subset of $B$ (and likewise for $B$ to be a proper superset of $A$), there must be at least one element of $B$ which is not in $A$. This is because if there are no elements in $B$ that are not in $A$, then they would be equal.

---

The symbol for proper subset is $\subset$, and the symbol for proper superset is $\supset$.

- $A \subset B$ means '$A$ is a subset of $B$'
- $B \supset A$ means '$B$ is a superset of $A$'

These two statements mean the same thing: every element in $A$ is also in $B$, but $A$ is not equal to $B$ (there is at least one element in $B$ that is not contained within $A$).

One easy way to remember all of this is that:

- the normal subset is like "less than or equal to"
- the normal superset is like "greater than or equal to"
- the proper subset is like "less than but not equal to"
- the proper superset is like "greater than but not equal to"

In symbols:

- $\subseteq$ is like $\le$
- $\supseteq$ is like $\ge$
- $\subset$ is like $\lt$
- $\supset$ is like $\gt$

Because you can always write that a set $M$ is a superset of a set $N$ by writing that $N$ is a subset of $M$, the superset and proper superset symbols aren't as prevalent as the subset and proper subset symbols. Just knowing $\subseteq$ (normal subset) and $\subset$ (proper subset) is enough to get by, so if you're feeling overwhelmed, focus on learning those.

---

Next: [[Nested Sets]]