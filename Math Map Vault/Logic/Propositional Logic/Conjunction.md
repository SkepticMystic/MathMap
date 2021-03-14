#propositional_logic 

# Conjunction

---

The logical operator **conjunction** combines two propositions into a new proposition in a way analogous to the word "and". This is why it's sometimes called the "AND" operator. Say we have the following two propositions:

- $P$ says "I am thirsty"
- $Q$ says "I am tired"

The conjunction of the two would be "I am thirsty and I am tired." Conjunction is symbolized with the '$\land$' symbol, so we could write this new proposition as $P \land Q$. This is read as "$P$ and $Q$".

The entire proposition $P \land Q$ is only true when both $P$ **and** $Q$ are true. In other words, if either $P$ or $Q$ are false, then the entire proposition is false. Hopefully this makes intuitive sense: the statement "I am thirsty and tired" should be true if I'm both thirsty and tired, but in all other cases (if I'm thirsty but not tired, or tired but not thirsty, or neither thirsty nor tired) it should be false.

 The key takeaway here is that the conjunction of two propositions is true if both original propositions are true, and is false in all other cases. Another way to look at it is if the conjunction of two propositions is true, then both of the original propositions must be true, and if the conjunction is false, then at least one of the original propositions must be false.
 
 Note that there are alternate symbols for the conjunction operator: some people use an asterisk, others use a dot, and still others use the word "AND". The conjunction of $P$ and $Q$ could be written as:

- $P \land Q$
- $P * Q$
- $P \cdot Q$
- $P~~AND~~Q$

---


Let's model the conjunction of two propositions using a truth table:

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

Reading the truth table, we see that:

- the first row tells us that if $P$ is false and $Q$ is false, $P \land Q$ is false
- the second row tells us that if $P$ is false but $Q$ is true, $P \land Q$ is false
- the third row tells us that if $P$ is true but $Q$ is false, $P \land Q$ is false
- the fourth row tells us that if $P$ is true and $Q$ is true, $P \land Q$ is true

Looking at the column under $P \land Q$, it's clear that the only time $P \land Q$ is true is when both $P$ and $Q$ are true. If either $P$ or $Q$ are false, $P \land Q$ is false.

---

Next: [[Disjunction]], [[Conditional]]