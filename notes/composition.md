## [Guy Rothblum, IAS](https://www.youtube.com/watch?v=RNqZJDAP1uU)

- Privacy Loss is a random variable, because it is measured over the outcome space drawn from the Mechanism M. Hence, we can study it's mean, variance, etc.

- Negative Privacy Loss: Privacy Loss is negative when the outcome of a query (after noise addition) persuades an observer to decrease confidence in the actual truth and increase the confidence or liklihood of the opposite event. Mathematically, this occurs when the probability of denominator is higher than that of the numerator.

- \delta serves a purpose similar to that in PAC algorithms, i.e. the privacy loss is within the specified bounds with a probability of (1 - \delta). Also, delta is cryptographically extremely small.

- Concentrated DP: The Privacy Loss, which is a random variable is forced to have a small mean and small variance. Specifically, the mean and variance are supposed to be smaller than a Gaussian distribution with the same parameters. Theory of subgaussians is used to prove properties of concentrated DP. 

References:
[DRV10] Advanced Composition: Error bounds on composing k algorithms
[DN03] Fundamental Law of Information Recovery: In DP, error must be atleast Sigma(sqrt(n))
[KOV15] Tight bounds on DP composition for Homogenous case
[MV16] Tight bounds on DP composition for Heterogenous case: computing optimal epsilon and delta is #P-Complete(even more harder than NP Complete)
[BS16] Concentrated DP with bounds on Renyi Divergences
