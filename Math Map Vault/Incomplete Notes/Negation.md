#propositional_logic 

# Negation

---

The **negation** (sometimes called the **logical complement**) of a proposition modifies it in a way analogous to the word "not". This is why negation is sometimes referred to as the "NOT" operator. The negation of a proposition results in a new proposition which always has the opposite truth value.

Say we have a proposition $P$ which says "The sky is blue." The negation of $P$ would be "The sky is **not** blue." We symbolize the negation of a proposition by putting either a $\neg$ or a \~ sign in front of it. They both mean the same thing, and are read as "not". So the negation of our proposition $P$ could be symbolized with $\neg P$ or \~$P$, and would be read as "not $P$".

We can see that in any given circumstance, the negation of $P$ has the opposite truth value as the original proposition $P$:

- If the sky is blue, then $P$ must be true, whereas $\neg P$ must be false.
- If the sky is not blue, then $P$ must be false, whereas $\neg P$ must be true.

The sky must either be blue or it must be not blue, so we've checked all cases, and in all cases the negation of $P$ has the opposite truth value as $P$.

Given any proposition, the negation can be obtained by adding a "not" into the proposition. Let's see a few more examples:
- $Q$ is "I am a dog."
	- $\neg Q$ is "I am not a dog."
- $R$ is "I am 2.1 meters tall."
	- $\neg R$ is "I am not 2.1 meters tall."

---

Let's model negation using a truth table:

<html>
	<table>
		<tr>
			<th>P</th>
			<th>¬P</th>
		</tr>
		<tr>
			<td>F</td>
			<td>T</td>
		</tr>
		<tr>
			<td>T</td>
			<td>F</td>
		</tr>
	</table>
</html>

- the first row says that if $P$ is false, the negation of $P$ is true
- the second row says that if $P$ is true, the negation of $P$ is false.

The key takeaway is that the negation of $P$ is the proposition which always has the opposite truth value as $P$.

---

Next: [[Double Negatives]]