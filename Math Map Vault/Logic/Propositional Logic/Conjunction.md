#propositional_logic 

# Conjunction

---
The logical operator **conjunction** is analogous to "and". It's the operator we used in our "Ted likes pie and Ted likes ice cream" example from earlier. The conjunction of any two propositions results in a new proposition which is only true when both of the original two propositions are true. This is why it's called "and".

Say we have the following two propositions:

- $P$ says "I am thirsty"
- $Q$ says "I am tired"

The conjunction of the two would be "I am thirsty and I am tired". Conjunction is symbolized with a '$\land$' symbol, so we could write this new proposition as $P \land Q$. This is read as "$P$ and $Q$", because if we substitute in $P$ and $Q$ then we get our proposition all worded out.

We know that $P \land Q$ is only true when both $P$ **and** $Q$ are true. If I'm  thirsty but not tired, or tired but not thirsty, or neither thirsty nor tired, then the statement "I am thirsty and I am tired" is clearly false. Is there a way to show this using a truth table?

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

The answer is yes! Remember that in a truth table, the top row shows the propositions under consideration, while each row below that represents one possible arrangement of truth values; the reason there are four rows of truth values is because there are four possible combinations of $P$ and $Q$.

Let's practice using the table by looking at the first situation (the first row of truth values): if $P$ is false and $Q$ is false, then $P \land Q$ is also false. If we look at the rest of the rows:

- the second row tells us that if $P$ is false but $Q$ is true, $P \land Q$ is false
- the third row tells us that if $P$ is true but $Q$ is false, $P \land Q$ is false
- the fourth row tells us that if $P$ is true and $Q$ is true, $P \land Q$ is true

Looking at the column under $P \land Q$, it's clear that the only time $P \land Q$ is true is when both $P$ and $Q$ are true.

---

Next: [[Disjunction]], [[Conditional]]