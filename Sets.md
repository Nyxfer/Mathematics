## Sets

###1. Number sets

- Natural numbers (N)

- Integer numbers (Z)

  - countable infinite set

- Rational numbers (Q)

  - countable infinite set
  - $ Q = \lbrace \cfrac{a}{b} : a, b \in Z, b \neq 0 \rbrace $

- Irrational numbers

- Real numbers (R)

  - uncountable set

- Complex numbers (C)

  ​	C = $\lbrace a + ib : a, b \in R \rbrace $, where $ i^2 = -1$

### 2. Set Builder Notation

- $X = \lbrace expression : rule \rbrace $

### 3. Set Equality

- If $A \subset B \ and \ B \subset A $, then $A = B$
- $\emptyset \neq \lbrace \emptyset \rbrace$, but $ \emptyset \in \lbrace \emptyset \rbrace $.

### 4. Cartesian product

- $ X \times Y = \lbrace (x, y) | x \in X \bigwedge y \in Y \rbrace $

### 5. Subsets

- If $ x \in B$ for every $x \in A$, then set $A$ is subset of set $B$. The notation used to denote this is $ A \subseteq B$.
- For any set $X$, $\emptyset \subseteq X$.
- For any set $X$ with members, $\emptyset \subset X$. 

### 6. Power Set

Definition: The power set of any set $S$ is the set of all subset of $S$, including the $\emptyset$ and $S$ itself, denoted as $\wp(S)$, $P(S)$ or $2^S$. Any subset of $P(S)$ is called a *family of sets* over $S$.

- If $S$ is a finite set with $|S| = n$ elements, then the number of subsets of $S$ is $|\wp(S)| = 2^n$.

### 7. Union, Intersection, Difference

- $ A \bigcup B = \lbrace x : x \in A  \ or\  x \in B \rbrace = B \bigcup A$
- $ A \bigcap B = \lbrace x : x \in A \ and \ x \in B \rbrace = B \bigcap A$
  - if $ A\bigcap B = \emptyset $, then $A$ and $B$ are *disjoint*.
- $ A - B = \lbrace x : x \in A \ and \ x \notin B \rbrace $
- $ B - A = \lbrace x : x \in B \ and \ x \notin A \rbrace $
  - $ A - B \neq B - A$
  - if $ A \subseteq B$, then $A - B = \emptyset$.
- $A \bigcup (B \bigcap C) = (A \bigcup B) \bigcap (A \bigcup C)$
- $ A \bigcap (B \bigcup C) = (A \bigcap B) \bigcup (A \bigcap C) $

### 8. Complement

Definition: Let $A$ be a set with a universal set $U$. The complement of $A$, denoted $\overline{A}$ or $A'$, is the set $\overline{A} = U - A$.

- $ A \bigcup \overline{A} = U$
- $A - \overline{A} = A$
- de Morgan laws (3)
  - $A \bigcap \overline{A} = \emptyset$
  - $\overline{A \bigcup B} = \overline{A} \bigcap \overline{B}$
  - $\overline{A \bigcap B} = \overline{A} \bigcup \overline{B}$

### 9. Injective, Surjective, Bijective Functions

- injective, if $ f(x) = f(y) -> x = y (here\ x, y \in A)$
- ​