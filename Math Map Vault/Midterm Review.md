**1.** Prove the following by induction:
Show that $n^2 \lt 3^{n+1}$:
- $P(1)$ is true: $1 \lt 3^2 = 9$
- $P(2)$ is true: $4 \lt 3^3 = 27$
- Assume $P(k)$ is true:  $k^2 \lt 3^{k+1}$
- Show that $P(k + 1)$ is true: $(k+1)^2 \lt 3^{k+1+1}$
- $k^2 + 2k + 1 \lt 3^{k+2}$
- $(k^2) + (2k + 1) \lt (3^{k+1}) + (2k+1)$
- $2k + 1 < k^2 < 3^{k + 1}$
- $(k^2) + (2k + 1) \lt (3^{k+1}) + (2k+1) \lt (3^{k+1}) + (3^{k+1})$
- $(k^2) + (2k + 1) \lt (3^{k+1}) + (2k+1) \lt (3^{k+1}) + (3^{k+1}) \lt (3^{k+1}) + (3^{k+1}) + (3^{k+1})$
- $(k^2) + (2k + 1) \lt (3^{k+1}) + (2k+1) \lt (3^{k+1}) + (3^{k+1}) \lt 3^1 * (3^{k+1})$
- $(k^2) + (2k + 1) \lt (3^{k+1}) + (2k+1) \lt (3^{k+1}) + (3^{k+1}) \lt (3^{k+1+1})$

Show that $1+3+5+⋯+(2n−1)=n^2$ for all $n \ge 1$
- $P(1)$ is true: $1 = 1^2$
- $P(2)$ is true: $1 + 3 = 2^2$
- Assume $P(k)$ is true: $1+3+5+⋯+(2k−1)=k^2$
- Show that $P(k+1)$ is true: $1+3+5+⋯+(2(k+1)−1)=(k+1)^2$
- $1+3+5+⋯+(2k + 1)=(k+1)^2$
- $k^2 + (2k + 1)=(k+1)^2$
- $k^2 + 2k + 1 = k^2 + 2k + 1$


Show that $12^n - 1$ is divisible by $11$
- $P(1)$ is true: $12^1 - 1 = 11$
- $P(2)$ is true: $12^2 - 1 = 143 = 11*13$
- Assume $P(k)$ is true: $12^k - 1$ is divisible by 11
- Show that $P(k+1)$ is true: $12^{k+1} - 1$ is divisible by 11
- $12^{k+1} - 1$
- $12^k(12^1) - 1$
- $12^k(11)+12^k - 1$
- $[12^k(11)]+[12^k - 1]$
- \[divisible by 11] + \[divisible by 11] = \[divisible by 11]

**2.** Show that $\sqrt{7}$ is not a rational number.
Proof by contradiction:
- Assume that $\sqrt{7}$ is a rational number.
- Hence $\sqrt{7} = \frac{a}{b}$ where $\frac{a}{b}$ is in lowest terms.
- $7 = \frac{a^2}{b^2}$
- $7b^2 = a^2 = a*a$
- $a\ mod\ 7 = 0$
- $7*n = a$
- $7b^2 = (7n)^2 = 49*n^2$
- $b^2 = 7n^2$
- $b\ mod\ 7 = 0$
- $b = 7m$
- This is a contradiction because if $\frac{a}{b} = \frac{7n}{7m}$ then clearly $\frac{a}{b}$ couldn't have been in lowest terms.

**3.** Let $C = \{v, w, x, y, z\}$
a) $|C| = 5$, $|P(C)| = 32$
b) $M=$ {all strings of length 5 or less with letters from C}
![[Pasted image 20210308144153.png]]
$|M| = 5 + 5^2 + 5^3 + 5^4 + 5^5 = 3905$
c) $K=${all strings using letters from C}
$|K| = \aleph_0$
d)$E =$ {all strings of length 5 or less with letters from C and ending with the letter z}
$|E| = 1 + 5 + 5^2 + 5^3 + 5^4 = 781$
e)
![[Pasted image 20210308210730.png]]
f)
![[Pasted image 20210308211333.png]]
g) $K$ and $\mathbb{N}$ have a 1-to-1 correspondence with each other because each string in $K$ is generated in a finite number of steps, so we can order the strings based on the number of steps and thus construct a list of strings. This allows us to create a bijection.

**4.** Sets $A$, $B$, and $C$ are in a universe $U$. Show the following using indexing:
a) $((C-B) \cup A)’ = ( C \cap B) \cup (C \cup B)’$
![[Pasted image 20210308212047.png]]
- $(C - B) = 6, 7$
- $(C-B) \cup A = 1, 2, 5, 6, 7$
- $((C-B) \cup A)' = 3, 4, 8$
- $(C \cap B) = 5, 4$
- $(C \cup B) = 2, 3, 4, 5, 6, 7$
- $(C \cup B)' = 1, 8$
- $( C \cap B) \cup (C \cup B)’ = 5, 4, 1, 8$
- $((C-B) \cup A)’ \not= ( C \cap B) \cup (C \cup B)’$

b) $((C-B) \cup A)’ = ( C \cap B) \cup (C \cup B)’$ if $A \cap C = \emptyset$
![[Pasted image 20210308213926.png]]
- $(C - B) = 5$
- $(C-B) \cup A = 1, 2, 5$
- $((C-B) \cup A)' = 3, 4, 6$
- $(C \cap B) = 4$
- $(C \cup B) = 2, 3, 4, 5$
- $(C \cup B)' = 1, 6$
- $( C \cap B) \cup (C \cup B)’ = 4, 1, 6$
- $((C-B) \cup A)’ \not= ( C \cap B) \cup (C \cup B)’$


c)
![[Pasted image 20210308214420.png]]
- $(C - B) = 3$
- $(C-B) \cup A = 3, 1$
- $((C-B) \cup A)' = 2, 4$
- $(C \cap B) = 0$
- $(C \cup B) = 2, 3$
- $(C \cup B)' = 1, 4$
- $( C \cap B) \cup (C \cup B)’ = 1, 4$
- $((C-B) \cup A)’ \not= ( C \cap B) \cup (C \cup B)’$

**5.** $A = \{3, 4, 5, 8, 11\}$ $B=$ {even numbers}
a) Let $R_1$ be a relation on $A$ and $B$ such that $R_1 = \{(a, b) : a \in A, b \in B, a < b\}$. Find all $(a, b)$ in $R_1$.
- $(3, 4), (3, 6), (3, 8)...$
- $(4, 6), (4, 8), (4, 10)...$
- $(5, 6), (5, 8), (5, 10)...$
- $(8, 10), (8, 12), (8, 14)...$
- $(11, 12), (11, 14), (11, 16)...$

b) Let $R_2$ be a relation on $A$ and $B$ such that $R_1 = \{(a, b) : a \in A, b \in B, (a - b)\ mod\ 2 = 0\}$. Find all $(a, b)$ in $R_1$.
- any pair $(a, b)$ where $a = 4$ or $a = 8$ and $b$ is even

c) Neither of these relations is functions because they map the same element of the domain to multiple elements of the codomain.

**6.** $A = \mathbb{R}$ and $B = [-1, 1]$ $R = \{(a, b): a \in A, b \in B, b = sin(a)\}$
- $(0, 0) \in R$
- $(\pi/2, 1) \in R$
- $(\pi, 0) \in R$
$R$ is a function because $sin(x)$ is a function. Every input gets one and only one output.

**7.** Propositions $p$, $q$, and $r$ are as follows:
- $p$: Mike has a ticket to the concert.
- $q$: Mike can give me a ticket.
- $r$: I can go to the concert.

a) $(p \lor \neg p )\implies \neg q$

![[Pasted image 20210308135430.png]]
tautology

**8.** Write the following sentences using symbols:
a) $(\forall n \in \mathbb{N})(\exists m)(n \gt n)$
b) $(\exists a \in \mathbb{R})(\forall x \in [1, 100])(a \le x)$