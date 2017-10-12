% Assignment 6\
	Group 4

---
author: Hendrik Werner
date: \today
fontsize: 12pt
geometry: margin=5em
---

# 8
* $P_1$: Stundents who like Brussels sprouts
* $P_2$: Stundents who like Broccoli
* $P_3$: Stundents who like Cauliflower

$\begin{aligned}
	N &= 270\\
	N(P_1) &= 64\\
	N(P_2) &= 94\\
	N(P_3) &= 58\\
	N(P_1 P_2) &= 26\\
	N(P_1 P_3) &= 28\\
	N(P_2 P_3) &= 22\\
	N(P_1 P_2 P_3) &= 14\\
	N(P'_1 P'_2 P'_3) &= N - N(P_1) - N(P_2) - N(P_3) + N(P_1 P_2) + N(P_1 P_3) + N(P_2 P_3) - N(P_1 P_2 P_3)\\
	&= 270 - 64 - 94 - 58 + 26 + 28 + 22 - 14\\
	&= 116\\
\end{aligned}$

116 students like none of the three vegetables.

# 9
* $P_i$: membership in set $i$

$\begin{aligned}
	N(P_1) =&\ 100\\
	N(P_2) =&\ 100\\
	N(P_3) =&\ 100\\
	N(P_4) =&\ 100\\
	N(P_1 P_2) =&\ 50\\
	N(P_1 P_3) =&\ 50\\
	N(P_1 P_4) =&\ 50\\
	N(P_2 P_3) =&\ 50\\
	N(P_2 P_3) =&\ 50\\
	N(P_3 P_4) =&\ 50\\
	N(P_1 P_2 P_3) =&\ 25\\
	N(P_1 P_2 P_4) =&\ 25\\
	N(P_1 P_3 P_4) =&\ 25\\
	N(P_2 P_3 P_4) =&\ 25\\
	N(P_1 P_2 P_3 P_4) =&\ 5\\
	N =&\ N(P_1) + N(P_2) + N(P_3) + N(P_4)\\
	&- N(P_1 P_2) - N(P_1 P_3) - N(P_1 P_4) - N(P_2 P_4) - N(P_2 P_4) - N(P_3 P_4)\\
	&+ N(P_1 P_2 P_3) + N(P_1 P_2 P_4) + N(P_1 P_3 P_4) + N(P_2 P_3 P_4)\\
	&- N(P_1 P_2 P_3 P_4)\\
	=&\ 4 * 100 - 6 * 50 + 4 * 25 - 5\\
	=&\ 195\\
\end{aligned}$

There are 195 total elements in the four sets.

# 10

# 11
* $P_i$: divisible by $i$

There are only 4 squares of prime numbers which are less than 100.

$\begin{aligned}
	N &= 99\\
	N(P_4) &= \lfloor \frac{99}{4} \rfloor &&= 24\\
	N(P_9) &= \lfloor \frac{99}{9} \rfloor &&= 11\\
	N(P_{25}) &= \lfloor \frac{99}{25} \rfloor &&= 4\\
	N(P_{49}) &= \lfloor \frac{99}{49} \rfloor &&= 2\\
\end{aligned}$

$\begin{aligned}
	N(P'_4 P'_9 P'_{16} P'_{25} P'_{36} P'_{49} P'_{64} P'_{81} P'_{100}) &=\\
\end{aligned}$

# 12
First we partition the eight balls into 3 partitons, which can be done in $S(8, 3) = 966$ ways. Then we choose which of the partitions we put into which urn, which can be done in $3! = 6$ ways.

In total we can distribute the 8 balls in $966 * 6 = 5796$ ways.

# 13
## a
## b

# 14
$\begin{aligned}
	D_6 &= 6! \sum_{k = 0}^6 \frac{(-1)^k}{k!}\\
	&= 6! (1 - \frac{1}{2!} + \frac{1}{3!} - \frac{1}{4!} + \frac{1}{5!} - \frac{1}{6!})\\
	&= 455\\
\end{aligned}$

There are 455 derangements of the set $\{1, 2, 3, 4, 5, 6\}$.

$3!^2 = 36$ of these derangements end with $1, 2, 3$ in some order.

# 15
## a
## b
## c
