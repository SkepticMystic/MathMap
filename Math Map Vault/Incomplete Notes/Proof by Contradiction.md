#ProofMethod

# Proof By Contradiction

---

This method is used to prove a statement by showing that _if the negation were `True`_ then a contradiction would arise.

To show that $P$ is `True`, we try to show that $\neg~P\rightarrow \bot$.

This method is used to show that the empty set is a subset of _any_ set.

1. Suppose there is a set $X$ for which the empty set is **not** a subset of $X$. 
	$\emptyset\not\subset X$
	
2. By the definition of subsets, this implies that there is an element in $\emptyset$ that is not in $X$.

3. But $\emptyset$ is empty by definition! Thus we have a contradiction, the empty set can both be empty and have an element in it.

4. We therefore conclude that for any set $X$, $\emptyset\subset X$