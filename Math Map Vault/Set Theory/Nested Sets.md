#set_theory 

# Nested Sets

---

Is it possible to have a set which contains other sets? It turns out that the answer is yes. These don't have an agreed-upon official name, but you might call them "**nested sets**". Let's look at a concrete example to gain an intuition of this concept:

Say that there is a school which has three classrooms, taught by Professors Xeno, Yew, and Zora. Let's say that we gather all of the students in each class into their own set:

- $X = \{$students in Professor Xeno's class$\}$
- $Y = \{$students in Professor Yew's class$\}$
- $Z = \{$students in Professor Zora's class$\}$

Now let's suppose that we make a set of classrooms which we call $C$. There are clearly three classrooms, so $C$ will get the three sets $X$, $Y$, and $Z$: $$C = \{X, Y, Z\}$$

We've just made some nested sets: the sets $X$, $Y$, and $Z$ are now elements of an "umbrella" set $C$.

Something to note is that $C$ only contains three objects, meaning the cardinality of $C$ is three ($|C| = 3$). This is because although $C$ contains several classrooms ($X$, $Y$, and $Z$), the students inside of those classrooms are not elements of $C$, because students aren't classrooms.

---

Let's now examine a more abstract example: say we have a set $A$ and a set $B$:

- $A = \{u, v, w\}$
- $B = \{x, y, A\}$

In this case, $A$ is nested within $B$ (it's an element of $B$).

<html>
	<center>
		<svg width="200" height="200">
			<circle cx="100" cy="100" r="90" stroke="white" stroke-width="4" fill="none"/>
			<text x="25" y="25" fill="white">B</text>
			<text x="90" y="80" fill="white">x</text>
			<text x="70" y="130" fill="white">y</text>
			<text x="120" y="110" fill="white">A</text>
		</svg>
	</center>
</html>

We could "expand" the set $A$ inside of $B$ like so: $$B = \{x, y, \{u, v, w\}\}$$

Note that the elements $u$, $v$, and $w$ are *not* inside of $B$, just like how the students from the earlier example weren't in the set of classrooms. The elements $u$, $v$, and $w$ are inside of a set which is inside of $B$; this is a subtle but key difference. If we expand $A$ in our Euler diagram:

<html>
	<center>
		<svg width="200" height="200">
			<circle cx="100" cy="100" r="90" stroke="white" stroke-width="4" fill="none"/>
			<text x="25" y="25" fill="white">B</text>
			<text x="90" y="80" fill="white">x</text>
			<text x="70" y="130" fill="white">y</text>
			<text x="120" y="110" fill="white">{u, v, w}</text>
		</svg>
	</center>
</html>

Clearly, $u$, $v$, and $w$ are not elements of $B$. However, the set containing $u$, $v$, and $w$ is an element of $B$. In symbols: $$u, v, w \not\in B$$ $$\{u, v, w\} \in B$$

This nuanced distinction is very important: a set contains only the objects directly within it; if the objects directly within it happen to contain other objects, that has no bearing on the 'top-level' set.

Let's now figure out the cardinality of $A$ and $B$. $A = \{u, v, w\}$, so there are three elements within $A$, so $|A| = 3$. For $B$, you might be tempted to say that $|B| = 5$. However, the cardinality of a set refers to the number of objects it contains, and the set $A = \{u, v, w\}$ is only one object (even if that one object contains other objects). So $|B| = 3$.

---

Another common misconception people have is that they confuse subsets with nested sets. A subset is a set which shares all of its elements with some other set. For example, if $X = \{a\}$ and $Y = \{a, b, c\}$, $X$ is clearly a subset of $Y$, but $X$ is not nested within $Y$ ($X$ is not an element of $Y$). If $X \subseteq$ Y ($X$ is a subset of $Y$), $X \not\in Y$ ($X$ is not in $Y$).

<html>
	<center>
		<svg width="200" height="200">
			<circle cx="100" cy="100" r="90" stroke="red" stroke-width="4" fill="none"/>
			<circle cx="120" cy="120" r="40" stroke="blue" stroke-width="4" fill="none"/>
			<text x="25" y="25" fill="red">Y</text>
			<text x="90" y="80" fill="blue">X</text>
			<text x="30" y="80" fill="red">c</text>
			<text x="40" y="130" fill="red">b</text>
			<text x="120" y="110" fill="purple">a</text>
		</svg>
	</center>
</html>

However, let's suppose that $X = \{a\}$ and $Y = \{X, b, c\}$:

<html>
	<center>
		<svg width="200" height="200">
			<circle cx="100" cy="100" r="90" stroke="red" stroke-width="4" fill="none"/>
			<text x="25" y="25" fill="red">Y</text>
			<text x="90" y="80" fill="red">X</text>
			<text x="70" y="130" fill="red">b</text>
			<text x="120" y="110" fill="red">c</text>
		</svg>
	</center>
</html>

If we expand $X$ we get:

<html>
	<center>
		<svg width="200" height="200">
			<circle cx="100" cy="100" r="90" stroke="red" stroke-width="4" fill="none"/>
			<text x="25" y="25" fill="red">Y</text>
			<text x="90" y="80" fill="red">{a}</text>
			<text x="70" y="130" fill="red">b</text>
			<text x="120" y="110" fill="red">c</text>
		</svg>
	</center>
</html>

$a$ is not an element of $Y$ ($a \not\in Y$). $\{a\}$ is an element of $Y$ ($\{a\} \in Y$).

Hopefully you can see that because $a$ is in $X$ but is not in $Y$, $X$ cannot be a subset of $Y$. $X$ is an element of $Y$.

---

Next: [[Set Operations]]