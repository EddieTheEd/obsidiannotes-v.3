---
layout: default
title: "Number Sets Notes"
---
# Number Sets Notes

Here is a pretty good set diagram I stole from the internet:
(for now we ignore the complex stuff, its in the next part)
<img src="https://edsobsidiannotes.netlify.app/assets/Pasted image 20220422081915.png" style="width:100%;height:100%">

These are all the subsets for the **real** numbers
```ad-note
-   Real numbers: A value of a continuous quantity that can be represented as a distance on a line.
    -   Note: continuous, as real numbers include 1 and 0.1357108375103759831...

```

Within all the **real** numbers exists numerous **subsets** of numbers.

These are the definitions for all the subsets, starting from the "smallest":

**Natural/Counting Numbers:**

Numbers which are used for counting.

Ask your teacher whether it starts at 0 or 1, however from those numbers they increase by 1 all the way to infinity, e.g. :

$1, 2,3,4,5,6,7,8,9,10,11 \ ... \ \infty$

Notice that this set does not include negative numbers (or 0).

```ad-note

Side-Note: There are 2 accepted definitions of natural numbers:
    -   Traditional: Natural = set of positive integers {1,2,3...}
    -   Slightly new: Natural = set of non-negative integers {0,1,2,3...}
```

The range of all natural numbers goes from {$1, \infty$}

(or $0, \infty$)

**Integers:**

Whole numbers, **OR**
Fraction that can be simplified, so that the denominator is 1.

e.g. -42/2 is an integer, as it can be simplified to -21. However, -43/2 is not an integer as it is simplified to $-21 \ \frac{1}{2}$, which is not whole and thus not an integer.

Essentially, it's the natural numbers + all the negative whole numbers.

The range of all integers goes from {$-\infty , \ \infty$}.

**Rational:**

A rational number is any number that can be described as a fraction of 2 whole integers.

Therefore, all integers are rational (put them in a fraction, make the denominator 1)

However, numbers such as $\sqrt{2}$ are not rational as they cannot be expressed by a fraction.

```ad-seealso
title: Extension

The square root of 2 is not rational. Let’s use a proof by contradiction.

Assume $\sqrt{2}$ is rational. All rational numbers can be written in the form $\frac{p}{q}$ , where there are no common factors.

Therefore:

$(\sqrt{2})^2 = (\frac{p}{q})^2$

$2 = \frac{p^2}{q^2}$

$p^2 = 2q^2$

Therefore, $p^2$ is even, as all even numbers can be written in the form $2k$, where $k$ is some number. In this case, this number is $q^2$.

Given that $p^2$ is even, then p must also be even, as an even number squared is always even, however an odd number squared is not even.

Here's a slightly better proof for this relationship between numbers and their squares (but badly formatted (i dont have sadler spec book))

Case 1: p is even

Given $p = 2k$, $p^2 = (2k)^2 = 4k^2$

$\therefore p^2 = 2(2k^2)$ where in this case, the number multiplied by 2 is $2k^2$.

Case 2: p is odd

Given $p = 2k-1, p^2 = (2k-1)^2 = 4k^2-4k+1$

$4k^2 - 4k + 1 = 2(2k^2-2k) + 1$

Now, given $2(k) + 1 = 2(k + 1) -1$,

$2(2k^2-2k) +1 = 2(2k^2-2k+1) -1$

$\therefore$ $p^2$ is an odd number, following the rule $p = 2k -1$

in this case, $k = 2k^2 -2k+1$

Now, as $p^2$ is even, and $p$ is even, let $p = 2r$

Thus, our equation can be written as:

$4r^2 = 2q^2$.

$q^2 = 2(r^2)$

Thus, $q^2$ is even, where $k = r^2$.

As shown above, the square of a number’s parity (even or odd) is the same as the number’s parity. Therefore, $q$ is even.

However, this means that both $p$ and $q$ are even, and this contradicts our initial assumption that there are no common factors between $p$ and $q$ (even numbers have the common factor of 2).
```


Therefore, the statement $\sqrt{2} = \frac{p}{q}$ is false and thus $\sqrt{2}$ is not rational.
Numbers like 0.012342342134 are rational, ($\frac{6171171067}{500000000000}$) and so are all the integers. Numbers like $\pi$ and $e$ are not rational. (they cannot be expressed as a fraction)

Thus, all numbers that are **not** natural, **not** integers and **not** rational, are **real** (for now). This includes:
-   $\pi$
-   $e$
-   $\sqrt{3}$
-   1234.1237481237410283750134681039... (goes to infinity)

**You can also call them irrational!**

Here's some general notation for these sets

**Notation:**

| Name     | Symbol |
| -------- | ------ |
| Natural  | $\mathbb{N}$ |
| Integer  | $\mathbb{Z}$ |
| Rational |   $\mathbb{Q}$   |
| Real   |    $\mathbb{R}$   |

**Extras:**

| Name              | Symbol |
| ----------------- | ------ |
| Irrational        |   $\mathbb{I} \ or \ \mathbb{Q}^{'}$     |
| Complex           |   $\mathbb{C}$    |
| Positive Integers |    $\mathbb{Z}^+$    |
| Negative Integers |    $\mathbb{Z}^{-}$    |
| Imaginary   |   $\mathbb{i}$     |
