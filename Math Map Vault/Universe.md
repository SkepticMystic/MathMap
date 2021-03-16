#set_theory 

# Universe

---

In set theory, the word 'universe' has a special meaning. The **universe** (or universal set) is the collection of all objects we want to investigate in a given situation. In naive set theory, the universe is a set (although in axiomatic set theory we define it a little differently) which is by convention represented by $U$ or $I$.

Say we have two sets: $A$ and $B$. $A$ contains $u$ and $v$ while $B$ contains $x$ and $y$. The universe $U$ in this situation would be the set containing $u$, $v$, $x$, and $y$. So our three sets are as follows:

- $A = \{u, v\}$
- $B = \{x, y\}$
- $U = \{u, v, x, y\}$

We normally present the universe as a rectangle in our Euler diagrams:

<html>
	<center>
		<svg width="500" height="300">
			<rect x='2' y='18' width='496' height='280' stroke='white' stroke-width='4' fill='none' />
			<circle cx="125" cy="150" r="90" stroke="red" stroke-width="4" fill="none"/>
			<circle cx="375" cy="150" r="90" stroke="blue" stroke-width="4" fill="none"/>
			
			<text x="10" y="10" fill="white">U</text>
			<text x="65" y="65" fill="red">A</text>
			<text x="425" y="65" fill="blue">B</text>
			
			<text x="95" y="120" fill="red">u</text>
			<text x="125" y="170" fill="red">v</text>
			<text x="325" y="140" fill="blue">x</text>
			<text x="400" y="160" fill="blue">y</text>
		</svg>
	</center>
</html>

However, it's normally left out unless it's relevant to the topic at hand, so you won't see it most of the time.

---

Next: [[Subsets and Supersets]]