#propositional_logic 

# Conjunction

---
The logical operator **conjunction** combines two propositions into a new proposition in a way analogous to the word "and". You might recognize conjunction as the operator we used in our "Ted likes pie and Ted likes ice cream" example from earlier. Say we have the following two propositions:

- $P$ says "I am thirsty"
- $Q$ says "I am tired"

The conjunction of the two would be "I am thirsty and I am tired" (which is equivalent to saying "I am thirsty and tired"). Conjunction is symbolized with the '$\land$' symbol, so we could write this new proposition as $P \land Q$. This is read as "$P$ and $Q$".

The entire proposition $P \land Q$ is only true when both $P$ **and** $Q$ are true. In other words, if either $P$ or $Q$ are false, then the entire proposition is false. Hopefully this makes sense: if I'm  thirsty but not tired, or tired but not thirsty, or neither thirsty nor tired, then the statement "I am thirsty and tired" is clearly false.

 The key takeaway here is that the conjunction of any two propositions results in a new proposition which is only true when both of the original two propositions are true.

---

Now, let's model the conjunction of two propositions using a truth table:

<html>
	<table>
		<tr>
			<th>P</th>
			<th>Q</th>
			<th>P ∧ Q</th>
		</tr>
		<tr>
			<td>F</td>
			<td>F</td>
			<td>F</td>
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

Remember that in a truth table, the top row shows the propositions under consideration, while each row below that represents one possible scenario (in other words one possible arrangement of truth values).

Why are there four rows of truth values? The behavior of $P \land Q$ is entirely determined by what the truth values of $P$ and $Q$ are, so we can completely model the behavior of $P \land Q$ if we model every possible combination of truth values for $P$ and $Q$. There are four such possible combinations, each of which is one row of truth values.

Let's practice using the table by looking at the first situation (the first row of truth values): if $P$ is false and $Q$ is false, then $P \land Q$ is also false. If we look at the rest of the rows:

- the second row tells us that if $P$ is false but $Q$ is true, $P \land Q$ is false
- the third row tells us that if $P$ is true but $Q$ is false, $P \land Q$ is false
- the fourth row tells us that if $P$ is true and $Q$ is true, $P \land Q$ is true

Looking at the column under $P \land Q$, it's clear that the only time $P \land Q$ is true is when both $P$ and $Q$ are true.

---

Next: [[Disjunction]], [[Conditional]]