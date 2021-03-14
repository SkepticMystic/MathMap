#propositional_logic 

# Disjunction

---

The logical operator **disjunction** combines two propositions into a new proposition in a way analogous to the word "or". This is why it's sometimes called the "OR" operator. Say we have the two propositions from before:

- $P$ says "I am thirsty"
- $Q$ says "I am tired"

The disjunction of the two would be "I am thirsty or I am tired." Disjunction is symbolized with the '$\lor$' symbol, so we could write this new proposition as $P \lor Q$. This is read as "$P$ or $Q$".

The entire proposition $P \lor Q$ is true when either $P$ **or** $Q$ are true. In other words, the only time the entire proposition is false is if both $P$ and $Q$ are false. Hopefully this makes intuitive sense: the statement "I am thirsty or I am tired" should be true if I'm thirsty, if I'm tired, or if I'm both; if I'm neither, it should be false.

 The key takeaway here is that the disjunction of any two propositions results in a new proposition which is only false when both of the original two propositions are false.
 
   The key takeaway here is that the disjunction of two propositions is false if both original propositions are false, and is true in all other cases. Another way to look at it is if the disjunction of two propositions is false, then both of the original propositions must be false, and if the disjunction is true, then at least one of the original propositions must be true.
 
  Note that there are alternate symbols for the disjunction operator: some people use a plus sign, while others use the word "OR". The disjunction of $P$ and $Q$ could be written as:

- $P \lor Q$
- $P + Q$
- $P~~OR~~Q$

---

Now, let's model the disjunction of two propositions using a truth table:

<html>
	<table>
		<tr>
			<th>P</th>
			<th>Q</th>
			<th>P v Q</th>
		</tr>
		<tr>
			<td>F</td>
			<td>F</td>
			<td>F</td>
		</tr>
		<tr>
			<td>F</td>
			<td>T</td>
			<td>T</td>
		</tr>
		<tr>
			<td>T</td>
			<td>F</td>
			<td>T</td>
		</tr>
		<tr>
			<td>T</td>
			<td>T</td>
			<td>T</td>
		</tr>
	</table>
</html>

Reading the truth table, we see that:

- the first row tells us that if $P$ is false and $Q$ is false, then $P \lor Q$ is false
- the second row tells us that if $P$ is false but $Q$ is true, $P \lor Q$ is true
- the third row tells us that if $P$ is true but $Q$ is false, $P \lor Q$ is true
- the fourth row tells us that if $P$ is true and $Q$ is true, $P \lor Q$ is true

Looking at the column under $P \lor Q$, it's clear that the only time $P \lor Q$ is false is when both $P$ and $Q$ are false. If either $P$ or $Q$ are true, $P \lor Q$ is true.

---

Next: [[Negation]]