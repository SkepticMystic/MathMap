#set_theory 

# Notating Membership

---

There are a few ways we can show that some element, which we'll call $a$, belongs to some set, which we'll call $S$. One way is using the symbol for membership, which looks like this: $\in$

$\in$ means "in", so to show that $a$ is an element of $S$ we can write $$a \in S$$

This means "a is in S". It could also be read as:

- "a is an element of S"
- "a is a member of S"

Using our days in the week example, if the set $D$ is the collection of all of the days in the week, then we could show that 'Monday' is an element of $D$ with $$Monday \in D$$

Note that $\in$ does not imply exclusionary membership. If I write that $Monday \in D$, it doesn't mean that there are no other elements contained within $D$. It just means that one of the elements in $D$ is 'Monday'. It's possible that 'Monday' is the only element, but we don't know whether or not that is true based only on the statement $Monday \in D$.

A quick tie-in from propositional logic: $Monday \in D$ is an example of a proposition, because we've clearly asserted something which is either true or false. Every mathematical statement we make about set membership is going to assert that something is true (but our assertion could also be false), so every statement about set membership must be a proposition.

---

Another way we can show membership is with the $\ni$ symbol, which is the inverse of the $\in$ symbol. Whereas $\in$ means "in", $\ni$ means "contains".

This symbol is simply a different way to express the membership relation, where the set which groups the elements is written before the actual elements. So as an example, $$Q \ni b$$

means the same thing as $$b \in Q$$

They both say the same thing, but they each say it in different ways. The first one says "Q contains b" while the second one says "b is in Q".

Say that $M$ is the set of months in the year. We could write either $$January \in M$$
or $$M \ni January$$

This would say that "'January' is an element of M" or "M contains 'January'".

Note that like $\ni$, like $\in$, is not exclusionary. Writing $January \in M$ or $M \ni January$ doesn't mean that 'January' is the only element in $M$. It just asserts that one of the elements in $M$ is 'January'.

Although the standard notation is that you use $\in$, not $\ni$, both are useful to know.

---

Let's now examine some examples where we group multiple items together into a set. Suppose that we have a set $V$ and we want to put elements $j$, $k$, and $l$ inside of it. We would say that $$j, k, l \in V$$

which could be read as:
- "j, k, and l are inside V"
- "j, k, and l are elements of V"
- "j, k, and l are members of V"

We could say the same thing with $$V \ni j, k, l$$

which would be read as "V contains j, k, and l".

Remember that we're not too concerned about what type of things $a$, $b$, and $c$ are. They could stand for numbers, cars, puppies, or people - it makes no difference to us right now. We just care about the concept of grouping elements inside of sets.

Continuing our example from earlier, I could say that if the set $M$ is the set of months, then
$$October,\ March,\ December \in M$$

---

Next: [[Notating Non-Membership]]