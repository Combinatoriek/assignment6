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
We can use the same principle as for sets, except that everything is divided by $n$.

$p(E) = \frac{N(E)}{N}$

We know that $p(E'_1 \cap E'_2 \cap E'_3 \cap E'_4) = 0$

$\begin{aligned}
	p(E_1 \cup E_2 \cup E_3 \cup E_4) =&\ 1\\
	&- p(E'_1) - p(E'_2) - p(E'_3) - p(E'_4)\\
	&+ p(E'_1 \cap E'_2) + p(E'_1 \cap E'_3) + p(E'_1 \cap E'_4) + p(E'_2 \cap E'_3) + p(E'_2 \cap E'_4) + p(E'_3 \cap E'_4)\\
	&- p(E'_1 \cap E'_2 \cap E'_3) - p(E'_1 \cap E'_2 \cap E'_4) - p(E'_1 \cap E'_3 \cap E'_4) - p(E'_2 \cap E'_3 \cap E'_4)\\
	&+ 0\\
\end{aligned}$

# 11
* $P_i$: divisible by $i$

There are only 4 squares of prime numbers which are less than 100.

$\begin{aligned}
	N &= 99\\
	N(P_4) &= \lfloor \frac{99}{4} \rfloor &&= 24\\
	N(P_9) &= \lfloor \frac{99}{9} \rfloor &&= 11\\
	N(P_{25}) &= \lfloor \frac{99}{25} \rfloor &&= 3\\
	N(P_{49}) &= \lfloor \frac{99}{49} \rfloor &&= 2\\
	N(P_4 P_9) &= \lfloor \frac{99}{36} \rfloor &&= 2\\
\end{aligned}$

$\begin{aligned}
	N(P'_4 P'_9 P'_{25} P'_{49} =&\ N\\
	&- N(P_4) - N(P_9) - N(P_{25} - N(P_{49}))\\
	&+ N(P_4 P_9) + N(P_4 P_{25}) + N(P_4 P_{49}) + N(P_9 P_{25}) + N(P_9 P_{49} + N(P_{25} P_{47}))\\
	&- N(P_4 P_9 P_{25}) - N(P_4 P_9 P_{49}) - N(P_4 P_{25} P_{49}) - N(P_9 P_{25} P_{49})\\
	&+ N(P_4 P_9 P_{25} P_{49})\\
	=&\ 99 - 24 - 11 - 3 - 2 + 2\\
	=&\ 61\\
\end{aligned}$

# 12
First we partition the eight balls into 3 partitons, which can be done in $S(8, 3) = 966$ ways. Then we choose which of the partitions we put into which urn, which can be done in $3! = 6$ ways.

In total we can distribute the 8 balls in $966 * 6 = 5796$ ways.

# 13
## a
## b
$\begin{aligned}
	D_n &= (n - 1)(D_{n - 1} + D_{n - 2})\\
	&= n D_{n - 1} - D_{n - 1} + (n - 1) D_{n - 2}\\
	D_n - n D_{n - 1} &= D_{n - 1} + (n - 1) D_{n - 2}\\
\end{aligned}$

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
i. If exactly two letters end up in their correct envelope, then $6 - 2 = 4$ letters are deranged. There are $D_4 = 9$ derangements. We need to choose which two letters end up in the correct envelope, there are $\binom{6}{2}$ possibilities. The probability that exactly two letters end up in the correct envelope is

	$\begin{aligned}
		\frac{9 * 15}{6!} &= \frac{135}{720}\\
		&= \frac{27}{144}\\
		&= \frac{3}{16}\\
	\end{aligned}$

ii. By the same principle as (i):

	$\begin{aligned}
		\frac{\binom{6}{1} D_1}{6!} &= \frac{6 * 0}{720}\\
		&= 0\\
	\end{aligned}$

## b
We put unlabeled objects into labeled boxes. We know there are $\binom{n + k - 1}{k - 1}$ possibilities to do this.

For $n = 14, k = 3$ this is $\binom{14 + 3 - 1}{3 - 1} = \binom{16}{2}$.

## c
* $P_x$: $x \geq 4$
* $P_y$: $y \geq 5$
* $P_z$: $z \geq 8$

$N = \binom{16}{2}$ (see b)

To know how many distributions exist with $x \geq 4, y \geq 5, z \geq 8$ respectively, we first put 4 balls into $x$, then divide the rest, then put 5 balls into $x$ and divide the rest, \dots. Then we sum the possibilities:

* $N(P_x)$:

	$\begin{aligned}
		\sum_{i = 4}^{14} \binom{14 - i + 2 - 1}{2 - 1}
		&= \binom{11}{1} + \binom{10}{1} + \binom{9}{1} + \dots + \binom{1}{1}\\
		&= 11 + 10 + 9 + \dots + 1\\
		&= 66
	\end{aligned}$

* $N(P_y)$:

	$\begin{aligned}
		\sum_{i = 5}^{14} \binom{14 - i + 2 - 1}{2 - 1}
		&= \binom{10}{1} + \binom{9}{1} + \binom{8}{1} + \dots + \binom{1}{1}\\
		&= 10 + 9 + 8 + \dots + 1\\
		&= 55
	\end{aligned}$

* $N(P_z)$:

	$\begin{aligned}
		\sum_{i = 8}^{14} \binom{14 - i + 2 - 1}{2 - 1}
		&= \binom{7}{1} + \binom{6}{1} + \binom{5}{1} + \dots + \binom{1}{1}\\
		&= 7 + 6 + 5 + \dots + 1\\
		&= 28
	\end{aligned}$

Next we put 4 balls into $x$, and 5 balls into $y$, then the remaining ones into $z$. After that we do $x = 4, y = 6$, \dots. Then we sum the possibilities:

* $N(P_x P_y)$:

	* $x = 4, y = 5$
	* \dots
	* $x = 4, y = 10$
	* $x = 5, y = 5$
	* \dots
	* $x = 9, y = 5$

	$\begin{aligned}
		N(P_x P_y)
		&= \sum_{i = 4}^{14 - 5} (14 - i - 5 + 1)\\
		&= (14 - 4 - 5 + 1) + (14 - 5 - 5 + 1) + \dots + (14 - 9 - 5 + 1)\\
		&= 6 + 5 + \dots + 1\\
		&= 21\\
	\end{aligned}$

* $N(P_x P_z)$:

	$\begin{aligned}
		N(P_x P_z)
		&= \sum_{i = 4}^{14 - 8} (14 - i - 8 + 1)\\
		&= (14 - 4 - 8 + 1) + (14 - 5 - 8 + 1) + (14 - 6 - 8 + 1)\\
		&= 3 + 2 + 1\\
		&= 6\\
	\end{aligned}$

* $N(P_y P_z)$:

	$\begin{aligned}
		N(P_y P_z)
		&= \sum_{i = 5}^{14 - 8} (14 - i - 8 + 1)\\
		&= (14 - 5 - 8 + 1) + (14 - 6 - 8 + 1)\\
		&= 2 + 1\\
		&= 3\\
	\end{aligned}$

* $N(P_x P_y P_z)$:

	$4 + 5 + 8 > 14$, so $N(P_x P_y P_z) = 0$.

$\begin{aligned}
	N =&\ 120\\
	N(P_x) =&\ 66\\
	N(P_y) =&\ 55\\
	N(P_z) =&\ 28\\
	N(P_x P_y) =&\ \\
	N(P_x P_z) =&\ \\
	N(P_y P_z) =&\ \\
	N(P_x P_y P_z) =&\ 0\\
	N(P'_x P'_y P'_z) =&\ N\\
	&- N(P_x) - N(P_y) - N(P_6)\\
	&+ N(P_x P_y) + N(P_x P_z) + N(P_y P_z)\\
	&- N(P_x P_y P_z)\\
	=&\ 120\\
	&- 66 - 55 - 28\\
	&+ \\
	&- 0\\
\end{aligned}$
