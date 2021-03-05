#logic 
# Propositional Variables
It is often useful to represent propositions using symbols. We call these symbols **propositional variables**. We usually use uppercase English letters or lowercase Greek letters. For example, we can assert that $P$ represents the proposition "Dori's birthday is on April twentieth".

Some more examples:
- $Q$ could represent the proposition "Marge is in a playground."
- $\phi$ could represent the proposition "Aleph is a Hebrew letter."
- $\psi$ could represent the proposition "Debussy was not an impressionist composer."

Note that in the examples above, each proposition has a truth value. For example, the proposition $\phi$ has the truth value 'true' assigned to it (because aleph is indeed a Hebrew letter). As another example, $\psi$ has the truth value 'false' assigned to it (because Debussy was in fact an impressionist composer).

### Propositions as abstract objects

At this point we can begin to talk about propositions in a very abstract way. Because we know that all propositions have a truth value with two possible states ('true' and 'false'), we don't need to know the actual contents of the proposition to manipulate it.

To see why, take an example proposition $P$. We know it will either be true or it will be false, so if we first model its behavior assuming that it's true, and then do the same assuming it's false, we'll know the entirety of its behavior. We don't need to worry about the contents at all.

This is useful because our goal in studying propositional logic is to build rules about how we can combine and manipulate propositions. For our rules to be useful, they need to apply *universally*, meaning to all propositions, so it's helpful if we can model every proposition in the same way. Modeling propositions with symbols in a way that doesn't depend on the contents of the proposition fits the bill.

Next: [[Logical Operators]]