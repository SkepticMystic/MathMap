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

Let's revisit our cars and vehicles example from earlier: if $C$ is the set of all cars, and $V$ is the set of all vehicles, then we already established that $C$ is a subset of $V$. But is $C$ a proper subset of $V$?

<html>
	<center>
		<svg width="200" height="200">
			<circle cx="100" cy="100" r="90" stroke="red" stroke-width="4" fill="none"/>
			<circle cx="120" cy="120" r="40" stroke="blue" stroke-width="4" fill="none"/>
			<text x="25" y="25" fill="red">V</text>
			<text x="90" y="80" fill="blue">C</text>
		</svg>
	</center>
</html>

Yes it is: there are some vehicles which are not cars, and as long as there is one element in $V$ which is not in $C$, $V$ is a proper superset of $C$ (or, put another way, $C$ is a proper subset of $V$). How can we write this using symbols?

The symbol for proper subset is $\subset$, and the symbol for proper superset is $\supset$.

- $C \subset V$ means '$C$ is a proper subset of $V$'
- $V \supset C$ means '$V$ is a proper superset of $C$'

These two statements mean the same thing: every car in $C$ is also in $V$, but $C$ is not equal to $V$ (there is at least one vehicle in $V$ that is not contained within $C$).

One easy way to remember all of the symbols is:

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