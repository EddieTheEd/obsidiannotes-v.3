---
layout: default
title: "R-AESPE-7"
---

## Counting permutations using the inclusion/exclusion principle

Useful when considering the union of a few sets.

### Set Theory Notation
- $A\cup B$  - the **union** of $A$ and $B$
- $A \cap B$ - the **intersection** of $A$ and $B$
- $n(A)$ or $|A|$  - the **size of/number of elements in**  $A$

Size of a union of 2 sets:
- If $|A| = 9$ and $|B| = 10$, what is $|A \cup B|$ ?
	- We can't do this because we don't know how many elements are in both $A$ and $B$. Hence this is ambiguous.
- Hence the solution is $|A \cup B| = |A| + |B| - |A \cap B|$
	- This is because if we add $A$ and $B$ directly, we count the elements that are in both sets twice. Hence we remove the intersection to remove the duplicates.

Size of a union of 3 sets:
- $|A \cup B\cup C| = |A|+|B|+|C| - |A\cap B| - |A\cap C|-|B\cap C| + |A\cap B\cap C|$

Size of a union of 4 sets:
- $|A\cup B\cup C\cup D| = |A|+|B|+|C|+|D| - |A\cap B|-|A\cap C|-|A\cap D|-|B\cap C|-|B\cap D|-|C\cap D|+|A\cap B\cap C|+|A\cap B\cap D|+|A\cap C\cap D|+|B\cap C\cap D|-|A\cap B\cap C\cap D|$
## Applications to counting permutations
- e.g. find the number of permutations of digits taken 3 at a time where the digits can be drawn either all from 1,2,3,4,5 or 3,4,5,6,7.
	- Let $A$ be the set of permutations of 3 digits from 1,2,3,4,5
	- Let $B$ be the set of permutations of 3 digits from 3,4,5,6,7

- What we need to calculate is the **union** of the few sets. 
- Hence, the answer is $|A \cup B| = |A| + |B| - |A \cap B|$
	- $= 60 + 60 - 6$
	- $= 114$

### Example 39
- How many integers from 1 to 140 inclusive are not divisible by 2,5,7
	- Let A, B, C be the sets of all integers from 1 to 140 that are divisible by 2, 5 and 7.
	- Hence, $|A \cup B\cup C| = |A|+|B|+|C| - |A\cap B| - |A\cap C|-|B\cap C| + |A\cap B\cap C|$
	- $= 70 + 28 + 20 - 14 -10 - 4 + 2$
	- $=92$
	- **Note**: These are the numbers that are **not divisible!**.
		- Hence, $= 140-92 = 48$


