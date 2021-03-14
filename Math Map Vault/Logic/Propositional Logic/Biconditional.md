#propositional_logic 

# Conditional

---

The **biconditional** logical operator combines two propositions into a new proposition in a way analogous to the phrase "if and only if". Say we have the following two propositions:

- $P$ says "I eat food"
- $Q$ says "I am hungry"

We can combine these two statements with the biconditional to get "I eat food if and only if I am hungry." The biconditional is symbolized with the $\iff$ symbol, so we could write "I eat food if and only if I am hungry" as $P \iff Q$. This is read as "$P$ if and only if $Q$".

Just like the conditional, it's very convenient to think of biconditional as a promise. In fact, biconditional is like making a stronger promise than normal conditional - one which goes both ways. $P \iff Q$ says "I eat food if and only if I'm hungry" - this essentially means that not only do I promise that if I am hungry, I will eat food ($Q$ -> $P$), but I also promise that if I eat food, I am hungry ($P$ -> $Q$). This eliminates the possibility of eating food when not hungry that the normal conditional left wide open.

With the biconditional, if I eat food and I am hungry, then I've kept my promise. Similarly, if I don't eat food and I'm not hungry, then I've also kept my promise. In other words, if both $P$ and $Q$ are true, or both $P$ and $Q$ are false, $P \iff Q$ is true.

However, if I eat food when I am not hungry, or don't eat food when I am hungry, then I've broken my promise and my statement that "I eat food if and only if I am hungry" is false. In other words, if $P$ is true and $Q$ is false, or $P$ is false and $Q$ is true, then $P \iff Q$ is false.

Interestingly enough, it turns out that the biconditional is essentially a test for truth-value equality: $P \iff Q$ is true if $P$ and $Q$ have the same truth value, whereas it's false if $P$ and $Q$ have different truth values. In other words, the biconditional can be used to assert that two propositions are equivalent to each other.

Also note that the conditional $P \iff Q$ is sometimes written as $P$ <-> $Q$.

---

Let's model the biconditional using a truth table:

<html>
	<table>
		<tr>
			<th>P</th>
			<th>Q</th>
			<th>P &lt;-&gt; Q</th>
		</tr>
		<tr>
			<td>F</td>
			<td>F</td>
			<td>T</td>
		</tr>
		<tr>
			<td>F</td>
			<td>T</td>
			<td>F</td>
		</tr>
		<tr>
			<td>T</td>
			<td>F</td>
			<td>F</td>
		</tr>
		<tr>
			<td>T</td>
			<td>T</td>
			<td>T</td>
		</tr>
	</table>
</html>

Reading the truth table, we see that:

- the first row tells us that if $P$ is false and $Q$ is false, then $P \iff Q$ is true
- the second row tells us that if $P$ is false but $Q$ is true, $P \iff Q$ is false
- the third row tells us that if $P$ is true but $Q$ is false, $P \iff Q$ is false
- the fourth row tells us that if $P$ is true and $Q$ is true, $P \iff Q$ is true

Looking at the column under $P \iff Q$, it should be clear that $P \iff Q$ is true when $P$ and $Q$ are the same, while $P \iff Q$ is false when $P$ and $Q$ are different.

---

Next: [[Negation]]