Total 18 marks

1) (4 marks) Write first 5 terms of the AP with values:
	a) $a = 4, d = 7$
	b) $a = -3, d = 0$
	c) $a=\frac{5}{3}, d = \frac{4}{3}$
	d) $a = 0.7, d = 0.3$
2) (3 marks) Find the $n^{th}$ term $a_n$ of the AP with the following values:
	a) $a = -4, d = 6, n = 5$
	b) $a = \frac{5}{3}, d = 2, n = 1$
	c) $a = 14, d = -2, n = 8$
3) (2 marks) Find value of $n$ where $a_n$ becomes 0:
	a) $a = 3$, $d = \frac{1}{3}$
	b) $a = -13.6$, $d = 1.7$
4) (1 mark) Find value of $d$ such that we will have an AP where $a_{1} = -40$, $a_{9}= 8$.
5) (1 mark) Find $a$ and $d$ for the marking scheme of this question set, from first question till fourth question.
6) (2 mark) Are the following terms an AP? If yes, give their $a$ and $d$ values.
	a) -7, 3, 13, 23
	b) 3, 6, 9, 15
7) (1 mark) Determine the AP whose 3rd term is 5 and the 7th term is 13.
8) (2 marks) How many two-digit numbers are divisible by 7
9) (2 marks) During undersea diving, a diver will start to experience nitrogen narcosis when the surrounding pressure reaches 4 atm (4 times the normal atmospheric pressure). For each meter you dive downward, the pressure increases by 0.1 atm. Starting from the surface, how many meters deep underwater can a diver reach safely? *(This is a factually accurate question, based on real world measurements)*


### Solutions
4\) $a_{1}=-40, a_{9}=8$
   $a = -40,$
   $a+(9-1)d = 8$
   $-40 + 8d = 8$
   $8d = 48$
   $d=6$

5\) The AP is 4,3,2,1.
   Here, a is 4, d is -1.
 
8\) Lets look at the series of numbers divisible by 7:
   7, 14, 21, 28, ...
   If you notice, it is actually an AP. As a general fact, all your multiplication tables are APs. So the multiples of 7 is AP with d = 7, multiples of 5 is an AP with d = 5, and so on.
   If the entire series of multiples of 7 is an AP, then any subsequence/section of the series is also an AP, with same d. In this question, we are looking at the section of just the 2 digit numbers among the multiples of 7. 
   *(More explanation for understanding: Think of it like, writing all the multiples of 7, then removing all the numbers which are not 2 digit. We would remove 1 digit numbers, and 3 digit and above. We don't have to remove any number in between the 2 digits, otherwise the AP series will break and no longer be an AP. So as long as we don't remove anything in the middle, just stuff at the start or at the end, then things are fine, our remaining set of numbers is still an AP.)*
   So for multiples of 7, we know that d = 7. What we want to find is n for the AP. The AP starts with the smallest 2 digit multiple of 7, and ends with the largest 2 digit multiple of 7. 
   $a = 14$, $a_{n} = 7*14=98$.
   We got $a$, $a_n$, $d$. From this we can figure out $n$.
   $a + (n-1)d = a_n$
   $14 + (n-1)7 = 98$
   $(n-1)7 = 84$
   $(n-1)=\frac{70+14}{7}= 10 + 2 = 12$ 
   *(See what I did there? instead of directly 84/7, I split 84 into easier to divide chunks, so can do mentally faster. Just a helpful tip, in case you didn't already know)*
   $n = 13$

9\) Judging by the way the pressure increases in a fixed amount per each meter deep, we can tell that the pressure values form an AP. 
   Lets look at pressure at every integer meter. Let h be the depth level, P be the pressure.
   At h = 0m, P = 1 atm (Because we are at the surface, regular atmospheric pressure)
   At h = 1m, P = 1.1 atm (Increases by 0.1 atm per meter downward)
   At h = 2m, P = 1.2 atm
   
   So there is an AP here for values of P. We will start counting at h = 0. So first element of the AP, $a = a_{1} = 1$ at h = 0, $a_{2} = 1.1$ at h = 1, $a_{3} = 1.2$ at h = 2. 
   If you notice, for $n^{th}$ value of AP $a_n$, h is equal to n-1. So after we find value of n, to get value of h, we do h = n-1. Just to remember to apply this in the end.
   
   Moving on to solve the AP, 
   $a = 1, a_{n} = 4, d = 0.1$
   $a + (n-1)d = a_n$
   $1 + (n-1) \cdot 0.1 = 4$
   $(n-1) \cdot 0.1 = 3$
   $(n-1) = 30$
   $n = 31$
   As established earlier, h = n-1. 
   Final h required: h = 31 - 1 = 30.
   The diver can dive 30 meters deep without risking nitrogen narcosis.