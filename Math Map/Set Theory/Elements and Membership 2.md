#set_theory 
# Elements and Membership 2
Let's now examine some examples where we put multiple items into a set. Suppose that we have a set $X$ and we put elements $a$, $b$, and $c$ inside of it. We would say that $$a, b, c \in X$$

which could be read as:
- "a, b, and c are inside X"
- "a, b, and c are elements of X"
- "a, b, and c are members of X"

We could say the same thing with $$X = \{a, b, c\}$$

which would be read as "X contains a, b, and c".

Right now, we're not too concerned about what type of things $a$, $b$, and $c$ are. They could stand for numbers, cars, puppies, or people - it makes no difference to us. We just care about the concept of putting elements inside of sets. If picturing them as objects to put in a shoebox helps you, go for it. If you're perfectly fine picturing this abstract idea of putting elements in a set, that's great too.

**Important Note:** no set can contain repeats of the same element multiple times. Writing $S = \{f, f\}$ just doesn't make sense in set theory. One way to think about it is that if you try to put multiple copies of the same object in a set, they get squished together into one copy of the object. So from the example above, the multiple $f$'s would get squished together into one $f$, and we'd get that $S = \{f\}$.

**Important Note:** objects in sets are unordered. The sets

- $A = \{j, k, l\}$
- $B = \{j, l, k\}$
- $C = \{k, l, j\}$
- $D = \{k, j, l\}$
- $E = \{l, j, k\}$
- $F = \{l, k, j\}$

are identical from a set theory perspective. $A = B = C = D = E = F$

As a final remark, you might see the symbol $\ni$ sometimes. It's the inverse of the $\in$ symbol. Whereas $\in$ means "in", $\ni$ means "contains".

This symbol is simply a different way to express the membership relation, where the set which contains the elements is written before the actual elements. So as an example $$m, n \in Z$$

means the same thing as $$Z \ni m, n$$

They both say that the set $Z$ contains elements $m$ and $n$, they just do it in different ways. The first one says "m and n are in Z" while the second one says "Z contains m and n". Another way you could write the same thing would be $$Z = \{m, n\}$$

Standard notation is that you use $\in$, not $\ni$, but in case you see it out in the wild, you know what it means.

Next: [[Limitations of the Physical Analogy]]
