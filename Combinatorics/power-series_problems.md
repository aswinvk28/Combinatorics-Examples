### Problems

[http://www.cs.cmu.edu/~rweba/algf09/solverecurrencesSF.pdf](http://www.cs.cmu.edu/~rweba/algf09/solverecurrencesSF.pdf)

Hi guys, I have an Exponential Power Series recursion here (real numbers). The answer is an array of length = 9

**It is written as:**

- if n for all whole numbers, and if n is even: it is the real number ^ n

- if n is odd, it is the product of the term at n/2 and the real number raised to n

**Rules:**

(1) Please make sure the resultant power series recursion is a differentiable one as all power series are, no matter the input is an integer

**Bonus Question:**

(2) Please also mention how many number of ways it connects with its input number counter part to reach its output

**Example1:**

n = 0, 1, 2, 3, 4, 5, 6, 7, 8,

t = 1, 3, 9, 27, 81, 2187, 729, 59049, 6561

Explanation

number / input = 3

t = 1, 3, 3^2, 3.3^2, 3^4, 3^2.3^5, 3^6, 3^3.3^7, 3^8

**Example2:**

n = 0, 1, 2, 3, 4, 5, 6, 7, 8

number / input = 1.01

t = 1, 1.01, (1.01)^2, 1.01*(1.01)^2, (1.01)^4, (1.01)^2*(1.01)^5, (1.01)^6, (1.01)^3*(1.01)^7, (1.01)^8

Answer = 1, 1.01, 1.0201, 1.030301, 1.04060401, 1.072135352, 1.061520151, 1.104622125, 1.082856706
