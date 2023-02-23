l
---
layout: default
title: "R-AESPE-3"
---

## Proofs

**Always just assume the conditional part of the statement**

## Funny Spec words
This is in "the realm of logic"
- Negation: The opposite of the statement, i.e. asserts the opposite
	- e.g. If: x is equal to 6
	- Negation: x is not equal to 6
	- e.g. If: n is greater than 12
	- Negation: n is less than or equal to 12
	- **We need negations to construct a contrapositive!**
- Converse: If, then content of conditional statement switched
	- e.g. If a polygon is a quadrilateral then it has exactly four sides.
	- Converse: If a polygon has exactly four sides then it is a quadrilateral.
	- e.g. If you were born in Australian, then you have been in AUstralia
	- Converse: If you have been in Australia, then you were born in Australia.
	- If the converse of a true statement is also true, then
	- $A \leftrightarrow B$
- Inverse: negate each of the if and then content
	- e.g. If a polygon is a quadrilateral then it has exactly four sides
	- Inverse: If a polygon is not a quadrilateral then it does not have exactly four sides.
- **Contrapositive**: Converse + Inverse, i.e. swap if, then content, and also negate!
	- i.e. If a polygon does not have exactly four sides, then it is not a quadrilateral
- De Morgan's Law
	- not(P and Q) = not(P) or not(Q)
	- not(P or Q) = not(P) and not(Q)

## Summary
Given a true conditional statement:
$$
If \ A \ then \ B
$$
- The **converse** (If $B$ then $A$) may or may not be true.
- The **inverse** (If not $A$ then not $B$) may or may not be true.
- The **negation** (If $A$ then not A) must be false given the statement is true.
- The **contrapositive** (If not $B$ then not $A$) is also true.

## Proof by Contrapositive


> [!Quote] 
> The "truth value" of a conditional statement and its contrapositive are always the same. That is, if a conditional statement is true its contrapositive is true, and if it were false then the contrapositive is false.

Example: "If $n^{2}+ 4n + 1$ is even, then $n$ is odd."

What to do? Find the contrapositive
Proof:

Contrapositive: "If n is even, then $n^{2}+ 4n + 1$ is odd."
let $n$ be even, i.e. $n=2k$ where $k \in \mathbb{Z}$

$\therefore n^{2}+ 4n + 1 = (2k)^{2}+ 4(2k) + 1$
$= 4k^{2}+ 8k + 1$
Hence $n^{2}+ 4n + 1 = 2(2k^{2}+4k) + 1,k \in \mathbb{Z},2k^{2}+4k \in \mathbb{Z}$
**Thus $n^{2}+ 4n + 1$ is odd since $2k^{2}+4k$* is an integer.*

**The contrapositive is true, hence the statement is true**
