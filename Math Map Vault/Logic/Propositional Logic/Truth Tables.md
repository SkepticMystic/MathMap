#propositional_logic 

# Truth Tables

---

At this point, we know that all propositions have a truth value with two possible states ('true' and 'false'). We also know that we can represent any given proposition without knowing what it actually says (by representing it with a propositional variable). These two facts allow us to model propositions very effectively in a rather abstract way.

To see how, take an example proposition $P$. We know it has to be either be true or false, so if we first model its behavior assuming that it's true, and then do the same assuming it's false, we'll know the entirety of its behavior. We don't need to worry about the contents at all.

One way to model propositions is with **truth tables**. A truth table is a table formed so that the top row is a list of propositions from left to right, while the cells under each proposition show possible truth values the propositions can have. Let's look at what a table with only our proposition $P$ might look like:

<html>
	<table>
		<tr>
			<th>Proposition:</th>
			<th>P</th>
		</tr>
		<tr>
			<th rowspan='2'>Values:</th>
			<td>F</td>
		</tr>
		<tr>
			<td>T</td>
		</tr>
	</table>
</html>

This is a pretty simple table, because for one proposition the only possible values are 'T' and 'F' ('true' and 'false'). However, we can make it a bit more complex by adding more propositions. For example, say we have two propositions, $P$ and $Q$. To model the entirety of their behavior, we'll need to model all possible combinations of truth values. There are four possibilities:

- both $P$ and $Q$ are false
- $P$ is false but $Q$ is true
- $P$ is true but $Q$ is false
- both $P$ and $Q$ are true

We can create a truth table which shows all of the possible combinations of truth values $P$ and $Q$ can have:

<html>
	<table>
		<tr>
			<th>Propositions:</th>
			<th>P</th>
			<th>Q</th>
		</tr>
		<tr>
			<th rowspan='4'>Values:</th>
			<td>F</td>
			<td>F</td>
		</tr>
		<tr>
			<td>F</td>
			<td>T</td>
		</tr>
		<tr>
			<td>T</td>
			<td>F</td>
		</tr>
		<tr>
			<td>T</td>
			<td>T</td>
		</tr>
	</table>
</html>

Each row of truth values in the table represents one possible combination of truth values for the propositions. So for example the first row has 'F', 'F', indicating that one of the possible combinations is that both $P$ and $Q$ are false.

Things quickly get more complicated when you add on more propositions: the truth table for three propositions $P$, $Q$, and $R$ looks like this:

<html>
	<table>
		<tr>
			<th>Propositions:</th>
			<th>P</th>
			<th>Q</th>
			<th>R</th>
		</tr>
		<tr>
			<th rowspan='8'>Values:</th>
			<td>F</td>
			<td>F</td>
			<td>F</td>
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
			<td>F</td>
			<td>T</td>
		</tr>
		<tr>
			<td>T</td>
			<td>T</td>
			<td>F</td>
		</tr>
		<tr>
			<td>T</td>
			<td>T</td>
			<td>T</td>
		</tr>
	</table>
</html>

As you can see, with three propositions there are a total of $8$ different possible combinations of truth values. Truth tables will be invaluable for modeling behaviors of more complex propositions.

---

Next: [[Logical Operators]]