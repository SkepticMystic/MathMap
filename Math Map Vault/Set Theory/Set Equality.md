#set_theory 
# Set Equality
Two sets are considered **equal** if they contain the exact same elements. So for example, say we have two sets: $M$ and $N$. If $M = \{a, b, c\}$ and $N = \{a, b, c\}$, $M = N$. Simple as that.

This probably makes intuitive sense, but we can also show that this follows from our concept of subsets. Two numbers, $a$ and $b$, are equal if both of the following are true: $$a \ge b$$ $$b \ge a$$

The only way both statements could be true is if $a = b$. We can make a similar argument with sets: given two sets, say $A$ and $B$, we can say that they are equal if both are subsets of each other. In other words, if both of the following are true: $$A \subseteq B$$ $$B \subseteq A$$

then $A = B$.

This is useful if we want to show that two sets are equal but can't do it directly by checking their elements. The reasoning is as follows:

If $A$ is a subset of $B$, then that means that all elements in $A$ are contained within $B$. let's make an Euler diagram for that:

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

However, we also know that every element in $B$ is also in $A$, so let's make an Euler diagram for that:

<html>
	<center>
		<svg width="400" height="400">
			<circle cx="200" cy="200" r="190" stroke="blue" stroke-width="4" fill="none"/>
			<circle cx="230" cy="230" r="80" stroke="red" stroke-width="4" fill="none"/>
			
			<text x="55" y="55" fill="blue">A</text>
			<text x="160" y="160" fill="red">B</text>
		</svg>
	</center>
</html>

The only way both of these things can be true at the same time is that they both contained exactly the same elements:

<html>
	<center>
		<svg width="400" height="400">
			<circle cx="200" cy="200" r="190" stroke="purple" stroke-width="4" fill="none"/>
			
			<text x="55" y="55" fill="blue">A</text>
			<text x="20" y="100" fill="red">B</text>
		</svg>
	</center>
</html>

---

Next: [[Proper Subsets and Proper Supersets]]