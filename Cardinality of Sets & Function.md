## Cardinality of Sets & Function

### Sets with Equal Cardinalities

Definition

- Two sets $A$ and $B$ have the *same cardinality*, written $|A| = |B|$, if there exists a bijective function $f : A  \rightarrow B$. If not, the sets have *unequal cardinalities*, that is, $|A| \neq |B|$.

Theorem

- $\exists \ f : N \rightarrow Z$, therefore $|N| = |Z|$.
- $\exists\  no \ f : N \rightarrow Z$, therefore $| N| \neq |R|$.

### Finite, Infinite, Countable and Uncountable Sets

Definition

- Set $A$ is ***countable infinite*** if $|N| = |A|$.
- Set A is ***uncountable*** if $A$ is infinite and $|N| \neq |A|$.
- $|N| = \aleph_0$, thus any countable infinite set has cardinality $\aleph_0$.

Theorem

- A set A is countable infinite if and only if its elements can be arranged in an infinite list $a_1, a_2, a_3, a_4, ...$
  - set $R$ is not countable infinite as meaning that it is impossible to write out all the elements of $R$ in an infinite list.
- The set $Q$ of rational numbers is countable infinite.
- If $A$ and $B$ are both countable infinite, then so is $A \times B$.
  - Given $n$ countable infinite sets $A_1, A_2, A_3, A_4, ... ,A_n$, with $n \geq 2$, the Cartesian product  $A_1\times A_2 \times A_3 \times A_4 \times ... \times A_n$ is also countable infinite.
- If $A$ and $B$ are both countable infinite, than $A \bigcup B$ as follows.

### Comparing Cardinalities

Definition

- suppose $A$ and $B$ are sets.
  1. $|A| = |B|$ means there is a bijection $A \rightarrow B$.
  2. $|A| < |B|$ means there is an injection $A \rightarrow B$, but no surjection $A \rightarrow B$.
  3. $|A| \leq |B|$ means $|A| = |B|$ or $|A| < |B|$.

Theorem

- If $A$ is any set, then $|A| < |\wp(A)|$.
- An infinite subset of a countable infinite set is countable infinite.
- If $U \subseteq A$, and $U$ is uncountable, then $A$ is uncountable.
- The Cantor-Bernstein-schroeder Theorem
  - If $|A| \leq |B|$ and $|B| \leq |A|$, then $|A| = |B|$. 
  - In other words, if there are injections $f:A  \rightarrow B$ and $ g : B \rightarrow A$, then there is a bijection $h : A\rightarrow B$.
- The set $R$ and $\wp(N)$ have the same cardinality.

Example

- $|N| < |R|$
- The intervals $[0, 1)$ and $(0,1)$ in $R$ have equal cardinalities.

