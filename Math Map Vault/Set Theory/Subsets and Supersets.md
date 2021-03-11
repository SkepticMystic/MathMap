#set_theory 
# Subsets and Supersets
---
A set $X$ is a **subset** of a set $Y$ if all elements in $X$ are also in $Y$. For example, suppose that $$X = \{a, c\}$$ $$Y = \{a, b, c, d\}$$

All of the elements in $X$ are also contained in $Y$, so $X$ is a subset of $Y$. The subset symbol is $\subseteq$, so we would write: $$X \subseteq Y$$

One way to remember this is that it's a little bit like the 'less than or equal to' symbol:
- $\subseteq$
- $\le$

**Superset** is the term we use if we look at the situation the other way around. If a set $Y$ contains all of the elements in $X$, then we would say $Y$ is a superset of $X$. The symbol for superset is $\supseteq$, so we would write: $$Y \supseteq X$$

One way to remember this is that it's a little bit like the 'greater than or equal to' symbol:
- $\supseteq$
- $\ge$

We can represent these concepts with an Euler diagram like so:

<html>
	<center>
		<svg width="400" height="400">
			<circle cx="200" cy="200" r="190" stroke="red" stroke-width="4" fill="none"/>
			<circle cx="230" cy="230" r="80" stroke="blue" stroke-width="4" fill="none"/>
			
			<text x="55" y="55" fill="red">Y</text>
			<text x="160" y="160" fill="blue">X</text>
			
			<text x="190" y="220" fill="white">a</text>
			<text x="270" y="250" fill="white">c</text>
			<text x="100" y="110" fill="white">b</text>
			<text x="220" y="90" fill="white">d</text>
		</svg>
	</center>
</html>

$a$ and $c$ are contained within both $X$ and $Y$, while $b$ and $d$ are contained only within $Y$.

- $X \subseteq Y$ because every element in $X$ is also contained within $Y$
- $Y \supseteq X$ because $Y$ contains all elements of $X$

---

We can also express that some set is *not* a subset or superset of some other set by writing the same symbol with a slash: $\not\subseteq$ or $\not \supseteq$

Given $X = \{a, c\}$ and $Y = \{a, b, c, d\}$ from above, we can say that

- $X \subseteq Y$ "Everything in $X$ is in $Y$"
- $Y \not\subseteq X$ "Not everything in $Y$ is in $X$"
- $X \not\supseteq Y$ "$X$ does not contain everything in $Y$"
- $Y \supseteq X$ "$Y$ contains everything in $X$"

Note that any set is a subset of itself and that the empty set is a subset of every set. So no matter what the contents of some set $S$ are, the following statements are always true:

- $S \subseteq S$
- $\emptyset \subseteq S$

You might be wondering how we know that the empty set is a subset of every set, and it's a pretty good question. Let's do a little thought experiment:

1. Suppose that the empty set was *not* a subset of some non-empty set $S$.
2. If statement 1 is true, that means the empty set must contain some element that's not inside $S$.
3. Clearly statement 2 can't be true because the empty set by definition contains no elements. Therefore, statement 1 must be incorrect.

---

Next: [[Set Equality]]