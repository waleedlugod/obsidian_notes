binomial characteristics:
* n identical trials
* each trial results in one of two outcomes
* probability of success is p and remains the same from trial to trial
* trials are independent
* interested in the binomial random variable x, the number of successes in n trials, for x = 0, 1, 2, ..., n

rule of thumb:
if the sample size islarge relative to population, if n/N >= 0.05, is not binomial

the binomial probability distribution
![[Pasted image 20230615154833.png]]

k: value of interest
n: trails
p: probability of success:
TRUE/FALSE: is cumulative
BINOM.DIST(k, n, p, TRUE or FALSE)
if TRUE: cumulative binomial probability: 0 to k
if FALSE: individual binomial probability: just k