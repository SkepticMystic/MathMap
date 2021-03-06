#set_theory 
# Set Equality
Two sets are **equal** if they contain the same elements. This makes intuitive sense, but we can also show that this follows from our concept of subsets. Two numbers, $a$ and $b$, are equal if both of the following are true: $$a \ge b$$ $$b \le a$$

The only way both statements could be true is if $a = b$. It's the same with sets. Given two sets, say $M$ and $N$, we can say that they are equal if both are subsets of each other. $$M \subseteq N$$ $$N \subseteq M$$

If both statements are true, they are equal: $M = N$.

Let's show why this is true with an example. Say that $$M = \{a, b\}$$ and $$N = \{a\}$$

$N$ is clearly a subset of $M$, but $M$ is not a subset of $N$. So they're not equal. What if we redefine $N$ so that $N = \{a, b, c\}$? Now, $M$ is a subset of $N$, but $N$ is no longer a subset of $M$. Let's try one more thing: $$M = \{a, b, c\}$$ $$N = \{a, b, c\}$$



Next: [[Proper Subsets and Proper Supersets]]