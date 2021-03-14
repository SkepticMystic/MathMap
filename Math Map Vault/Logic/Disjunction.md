#logic 
# Disjunction
---
Say we have two propositions: $P$ says "I am thirsty" while $Q$ says "I am tired". **Disjunction** allows us to combine these two into a new proposition with a new meaning. Disjunction is symbolized with a '$\land$' symbol and means "and", so if we were to write $P \land Q$, it would essentially  mean "$P$ and $Q$". In other words, our new proposition would read "I am thirsty **and** I am tired".

The fundamental property of disjunction is that the overall proposition we create is only true if **both** it's components propositions are true.

This operator's truth table is as follows:

| $P$     | $Q$     | $P~\land~Q$ |
| ------- | ------- | ----------- |
| `True`  | `True`  | `True`      |
| `True`  | `False` | `False`     |
| `False` | `True`  | `False`     |
| `False` | `False` | `False`     |