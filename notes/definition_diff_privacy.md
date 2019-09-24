## [The Definition of Differential Privacy - Cynthia Dwork](https://www.youtube.com/watch?v=lg-VhHlztqo)

- De-identified data isn't a solution because either it is not (1) useful data oe (2) de-identified at all. Specifically, de-identification does not hedge against linkage attacks, and against future revelation of auxilliary data sources.

> Fundamental Law of Info Reconstruction: Overly accurate estimations of many statistics is blatantly non private

Hence randomness is introduced i.e. some noise is added to the output of the asnwer of a mechanism.

- epsilon differential privacy definition is introduced. epsilon is the provacy loss. 

Takeaways:
- Group Privacy is multiplicative in epsilon. For a group os size k, the effective privacy loss factor is k * epsilon. (it is assumed that the members of the group are correlated)

- Composition of multiple diff. private mechanisms will add up the epsilons.

- Diff. Private(DP) algorithms are programmable - smaller fundamental units can be composed and put together more complicated DP algorithms.

- DP algorithms can be used for generalisation of underlying data even when privacy itself is not a privacy concern. This is possible because DP mechanisms are designed to reflect the data distribution rather than the individual points in the dataset.

