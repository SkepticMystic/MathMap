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

In summary so far: 

- $X \subseteq Y$ means '$X$ is a subset of $Y$'
- $Y \supseteq X$ means '$Y$ is a superset of $X$'

These two statements have identical meanings: "all elements in $X$ are also in $Y$" or "$Y$ contains all elements in $X$".

We can also express that some set is *not* a subset or superset of some other set by writing the subset/superset symbol with a slash: $\not\subseteq$ or $\not \supseteq$

Given $X = \{a, c\}$ and $Y = \{a, b, c, d\}$ from above, we can say that

- $X \subseteq Y$ "Everything in $X$ is in $Y$"
- $Y \not\subseteq X$ "Not everything in $Y$ is in $X$"
- $X \not\supseteq Y$ "$X$ does not contain everything in $Y$"
- $Y \supseteq X$ "$Y$ contains everything in $X$"

---

Euler diagrams are very useful for identifying subsets/supersets: if a set's circle is entirely within another set's circle, the first set must be a subset of the second set, and the second set must be a superset of the first set. This is because if the first set's circle is entirely within the second set's circle, all elements in the first set must also be in the second set. Let's now look at a few concrete examples of subsets, and make the Euler diagram for each.

First off, let's suppose that $V$ is the set of every single vehicle on the planet. Next, let's suppose that $C$ is the set of all cars on the planet. Clearly $C \subseteq V$, because all cars in $C$ will also be in $V$ (because all cars are vehicles). And, conversely, we could say that $V \supseteq C$.

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

Another example: suppose that $H$ is the set of all human beings, while $W$ is the set of all women, $M$ is the set of all men, and $N$ is the set of all nonbinary individuals. Clearly all of the elements of the set of women are also elements of the set of human beings, so $W \subseteq H$. The same reasoning applies for men and nonbinary individuals, so $M \subseteq H$ and $N \subseteq H$.

<html>
	<center>
		<svg width="200" height="200">
			<circle cx="100" cy="100" r="90" stroke="white" stroke-width="4" fill="none"/>
			<circle cx="70" cy="70" r="40" stroke="blue" stroke-width="4" fill="none"/>
			<circle cx="130" cy="130" r="40" stroke="yellow" stroke-width="4" fill="none"/>
			<circle cx="60" cy="140" r="20" stroke="green" stroke-width="4" fill="none"/>
			<text x="25" y="25" fill="white">H</text>
			<text x="160" y="100" fill="yellow">M</text>
			<text x="110" y="50" fill="blue">W</text>
			<text x="75" y="170" fill="green">N</text>
		</svg>
	</center>
</html>

Let's say that $S$ is the set of all students at your school. Let's also suppose that $T$ is the set of all teachers at your school and $P$ is the set of all people at your school. All elements of $S$ are also elements of $P$ (all students at the school are also people at the school), so $S \subseteq P$. Likewise, all elements of $T$ are also elements of $P$ (all teachers at the school are also people at the school), so $T \subseteq P$.

<html>
	<center>
		<svg width="200" height="200">
			<circle cx="100" cy="100" r="90" stroke="white" stroke-width="4" fill="none"/>
			<ellipse cx="130" cy="70" rx="65" ry='40' stroke="blue" stroke-width="4" fill="none" transform="rotate(45, 130, 70)" />
			<ellipse cx="70" cy="130" rx="65" ry='40' stroke="red" stroke-width="4" fill="none" transform="rotate(45, 70, 130)"/>
			<text x="25" y="25" fill="white">P</text>
			<text x="130" y="160" fill="red">T</text>
			<text x="60" y="50" fill="blue">S</text>
		</svg>
	</center>
</html>

Finally, say that the set $F$ is the set of fiction books, while the set $P$ is the set of paperback books:

<html>
	<center>
		<svg width="300" height="200">
			<circle cx="100" cy="100" r="90" stroke="red" stroke-width="4" fill="none"/>
			<circle cx="200" cy="100" r="90" stroke="blue" stroke-width="4" fill="none"/>
			<text x="25" y="25" fill="red">F</text>
			<text x="265" y="25" fill="blue">P</text>
		</svg>
	</center>
</html>

Clearly, $F \not\subseteq P$,  because there are elements in $F$ which are not inside of $P$ (namely fiction books that are not paperback). Additionally, $P \not\subseteq F$, because there are elements in $P$ which are not inside of $F$ (namely paperback books which are not fiction). So neither of these sets is a subset of the other. Remember, however, that both of them are subsets of the universal set $U$, which in this case maybe is the set of all books:


<html>
	<center>
		<svg width="300" height="200">
			<rect x='2' y='18' width='296' height='180' stroke='white' stroke-width='4' fill='none' />
			<circle cx="100" cy="110" r="80" stroke="red" stroke-width="4" fill="none"/>
			<circle cx="200" cy="110" r="80" stroke="blue" stroke-width="4" fill="none"/>
			<text x="125" y="10" fill="white">U</text>
			<text x="25" y="50" fill="red">F</text>
			<text x="265" y="50" fill="blue">P</text>
		</svg>
	</center>
</html>

This is because every fiction book is a book, and every paperback book is a book, so $F \subseteq U$ and $P \subseteq U$. Put another way, the universe is a superset of both $F$ and $P$: $U \supseteq F$ and $U \supseteq P$.

---

Two final notes: first, any set is a subset of itself. That is, $S \subseteq S$ for any set $S$. Hopefully this makes sense: $S$ has all of the elements as itself, so it must be a subset of itself. For the same reason, it's also a superset of itself.

Secondly, the empty set is a subset of every set. That is, $\emptyset \subseteq S$ for any set $S$. We can show that this is true with a little thought experiment:

1. Suppose that the empty set was *not* a subset of some non-empty set $S$.
2. If statement 1 is true, that means the empty set must contain some element that's not inside $S$.
3. Clearly statement 2 can't be true because the empty set by definition contains no elements. Therefore, statement 1 must be false.

---

Next: [[Set Equality]]