#set_theory 

# Subsets and Supersets

---

Suppose that we have two sets: 

- $X = \{a, c\}$
- $Y = \{a, b, c, d\}$

<html>
	<center>
		<svg width="400" height="400">
			<circle cx="200" cy="200" r="190" stroke="red" stroke-width="4" fill="none"/>
			<circle cx="230" cy="230" r="80" stroke="blue" stroke-width="4" fill="none"/>
			
			<text x="55" y="55" fill="red">Y</text>
			<text x="160" y="160" fill="blue">X</text>
			
			<text x="190" y="220" fill="purple">a</text>
			<text x="270" y="250" fill="purple">c</text>
			<text x="100" y="110" fill="red">b</text>
			<text x="220" y="90" fill="red">d</text>
		</svg>
	</center>
</html>

We can see that $a$ and $c$ are contained within both $X$ and $Y$, while $b$ and $d$ are contained only within $Y$. In other words:

- $a, c \in X$ and $a, c \in Y$
- $b, d \in Y$

Because every element in $X$ is also in $Y$ (there are no elements in $X$ that are not in $Y$), we would say that $X$ is a **subset** of $Y$. The subset symbol is $\subseteq$, so we would write: $$X \subseteq Y$$

One way to remember this is that it's a little bit like the 'less than or equal to' symbol:
- $\subseteq$
- $\le$

We can also look at the situation the other way around. Because $Y$ contains every element in $X$, we would say that $Y$ is a **superset** of $X$. The symbol for superset is $\supseteq$, so we would write: $$Y \supseteq X$$

One way to remember this is that it's a little bit like the 'greater than or equal to' symbol:
- $\supseteq$
- $\ge$

Euler diagrams like the one above are very useful for identifying subsets/supersets: if a set's circle is entirely within another set's circle, the first set must be a subset of the second set, and the second set must be a superset of the first set. This is because if the first set's circle is entirely within the second set's circle, all elements in the first set must also be in the second set.

In summary: 
- $X \subseteq Y$ means '$X$ is a subset of $Y$'
- $Y \supseteq X$ means '$Y$ is a superset of $X$'

These two statements have identical meanings: "all elements in $X$ are also in $Y$" or "$Y$ contains all elements in $X$".

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