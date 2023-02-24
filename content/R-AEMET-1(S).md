---
layout: default
title: "R-AEMET-1(S)"
---

For those who don't know the nomenclature i literally just made up, s = sai

## Two way tables

e.g. 

|                | B             | A               | Mi               | Total |
| -------------- | ------------- | --------------- | ---------------- | ----- |
| M              | 2% x 50% = 1% | 4% x 30% = 1.2% | 38% x 20% = 7.6% | 9.8%  |
| $\overline{M}$ | 49%           | 28.8%           | 12.4%            | 90.2%      |
| Total          | 50%           | 30%             | 20%              | 100%  |

This is a two way table?

1. Determine the probability that a randomly chosen dog has meningitis given that it is not mixed?
- Solution
	- $P(A|B) = \frac{P(A ∩B)}{P(B)}$
	- use your brain i can't be bothered to latex
2. Determine the probability that a dog with meningitis is blue eyed.
- Solution
	- See the two way table? Since this is a given question:
		- $P(B|M) = \frac{P(B∩M)}{P(M)}$
		- = $\frac{0.01}{0.098}$ = $10.2$ %

Class Explanation:
![](000_Files/000a_images/sai%20example%20q%20aemet%201.png)
(congrats to jonathan)

Big Q:
An 8 sided fair dice has the following set: {1,1,2,3,4,5,6,6}
It is rolled twice. Find probability that the sum of the two numbers is even.

Plot twist: don't draw "big ass tables", the probability is a half.
- For the sum to be even, the two numbers must be either both odd or both even. There is a $\frac{1}{2}$ probability to get an odd or even number both times you roll it. Hence the answer is $\frac{1}{4} \times \frac{1}{4} + \frac{1}{4} \times \frac{1}{4}$
- = $\frac{1}{2}$

Bigger: What is the probability that the second one is larger?
- Count in your head. Congratulations, you got the answer!!
- ($\frac{26}{64}$)
- Actually how you do it: 
	- Use the probabilities of each of the things

Bigger: What if sum is even and second is higher than first
- 1 -> 3,5 = 4/64
- 2 -> 4, 6, 6 = 3/64
- 3 -> 5 = 1/64
- 4 -> 6,6 = 2/64
- 5 = 0
- 6 = 0
- Therefore 10/64 = $P(s \ is \ even∩second >first)$

**Exercise to the reader: What is the probability of getting two distinct numbers?**

Q6:
Born in WA: 51%
Born in another country: 28%
Born in another state: 21%
Born in another country and have at least one other sibling: 80%
Born in WA, one or more siblings: 10%
Born in another state, at least 1 sibling: 35%
- Determine the probability that a student at PMS was not born in WA given that they have at least 1 sibling?
	- (28 x 80 + 35 x21)/28 x 80 + 35 x 21 + 51x10
	- = 85.4%
- prolly read a number wrong, pls check this is correct reader and email me

Q10:
- An elite group of avengers have to be chosen to investigate an incredible power surge on planet X. However taking 13 avengers would be an overkill. Thus only 7 avengers are to be chosen. If the avengers comprise of 2 tacticians, 2 recon masters, 4 attack leaders, 2 pilots and 3 combaters:
- a) What is the probability that all the attackers are selected:
	- 9C3= 84
	- 13C7 = 1716
	- Therefore probability = 84/1716 = 7/143 = 4.90%
- b) What is the probability that the team that has 4 attack leaders but will also have 2 combaters?
	- 6 * 3/1716 = 1.05%
- c) Determine the probability that the team has at least 1 tactician given that all recon masters are chosen.
	- 10/11
 $$\frac{\frac{2C_{1}\times2C_{2}\times10C_{4}}{13C_{7}}}{\frac{2C_{2}\times 11C_{5}}{13C_{7}}}$$
=
$$\frac{2C_{1}\times2C_{2}\times10C_{4}}{2C_{2}\times 11C_{5}}$$

Q12:
**"Think subset, or mutually exclusive"**
For the two events A and B, P(A) = 2/5, P(AUB) = 5/6
- a) Determine the minimum possible value of P(B)
	- In this case, they are mutually exclusive. Hence P(AUB) - P(A) = P(B)
	- Therefore P(B) = 13/30 or 0.433 recurring
- b) Determine the maximum possible value of P(A|B)
	- P(A|B) = $\frac{P(A\cap B)}{P(B)}$
	- We want B to be a subset. Therefore as B is inside A, $P(A\cap B)$ = $P(B)$, hence P(A|B) = 1

### Important note:
- If you want max value of P(A|B), use subset
- If you want min value of P(A/B) given P(AUB) use disjoint