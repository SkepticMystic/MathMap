#ProofMethod

# Proof By Contradiction

---

This method is used to prove a statement by showing that _if the [[negation]] were `True`_ then a [[contradiction]] would arise.

To show that $P$ is `True`, we try to show that $\neg~P\rightarrow \bot$.

This method is used to show that [[The Empty Set|the empty set]] is a [[Subsets and Supersets|subset]] of _any_ set.

1. Suppose there is a set $X$ for which the empty set is **not** a subset of $X$. 
	$\emptyset\not\subset X$
	
2. By definition of [[Subsets and Supersets|subsets]], this implies that there is an element in $\emptyset$ that is not in $X$.

3. But $\emptyset$ is empty by definition! Thus we have a contradiction, the empty set can both be empty and have an element in it.

4. We therefore conclude that for any set $X$, $\emptyset\subset X$