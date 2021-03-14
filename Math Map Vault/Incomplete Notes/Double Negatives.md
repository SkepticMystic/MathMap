#propositional_logic 

# Double Negatives

---

An interesting property of negation is that if you negate a proposition twice, you end up with the original proposition. This is known as **double negation**. Say we have the following propositions:

- $P$ says "Jake likes apples."
- $\neg P$ says "Jake doesn't like apples."
- $\neg \neg P$ says "Jake doesn't not like apples."

Clearly $P$ and $\neg \neg P$ have the same meaning, even if they say it in different ways. Because $P$ and $\neg \neg P$ have the same meaning, and hence always have the same truth values, we can use the biconditional to write the following proposition: $$P \iff \neg \neg P$$

This is known as the **double negation law**, and essentially says that any proposition is always equal to the proposition formed by negating it twice.

You can think of it as "pairs of negatives cancel each other out". This is useful if you have a proposition negated multiple times, such as $\neg \neg \neg P$: if pairs of negatives cancel each other out, then you can cancel two of the negations to find that $$\neg \neg \neg P \iff \neg P$$

In other words, "not not not $P$" is equivalent to saying "not $P$".

---