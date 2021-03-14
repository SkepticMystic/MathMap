#propositional_logic 

# Conditional

---

The **conditional** logical operator combines two propositions into a new proposition in a way analogous to the word "implies". This is why it's also known as "implication". Say we have the following two propositions:

- $P$ says "I am hungry"
- $Q$ says "I eat food"

We can combine them with the conditional to get "I am hungry implies that I eat food." You could equivalently say "If I am hungry, I eat food."

The conditional is symbolized with the '$\implies$' symbol, so we could write "If I am hungry, I eat food" as $P \implies Q$. This is read as "$P$ implies $Q$", or "If $P$, then $Q$."

The best way to think of the conditional is that it's a promise. Imagine that you say "If I am hungry, I eat food." If you do become hungry and then eat some food, you've kept your promise, so the statement "If I am hungry, I eat food" is true. However, if you become hungry and don't eat any food, then you've broken your promise, so the statement "If I am hungry, I eat food" is clearly false. Using our propositional variables, $P \implies Q$ is true if both $P$ and $Q$ are true, but false if $P$ is true and $Q$ is not true.

Your promise only says that if you are hungry, you'll eat food. This is good if you don't get hungry, because in that case it doesn't matter if you eat food or not. You'll have kept your promise either way. So if $P$ is false, $P \implies Q$ is true regardless of whether $Q$ is true or not.

Also note that the conditional $P \implies Q$ is sometimes written as $P$ -> $Q$.

---

Now, let's model implication using a truth table:

<html>
	<table>
		<tr>
			<th>P</th>
			<th>Q</th>
			<th>P -> Q</th>
		</tr>
		<tr>
			<td>F</td>
			<td>F</td>
			<td>T</td>
		</tr>
		<tr>
			<td>F</td>
			<td>T</td>
			<td>T</td>
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

- the first row tells us that if $P$ is false and $Q$ is false, then $P \implies Q$ is true
- the second row tells us that if $P$ is false but $Q$ is true, $P \implies Q$ is true
- the third row tells us that if $P$ is true but $Q$ is false, $P \implies Q$ is false
- the fourth row tells us that if $P$ is true and $Q$ is true, $P \implies Q$ is true

Looking at the column under $P \implies Q$, it should be clear that the only time $P \implies Q$ is false is when you "break your promise". If you say that if $P$ is true, $Q$ is also true, and then $P$ is true but $Q$ is false, you've broken your promise. You haven't said anything about any other cases, however, so for all the other cases your promise is kept and $P \implies Q$ is true.

---

Next: [[Biconditional]]