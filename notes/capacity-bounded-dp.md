[Work in Progress]<br>
Q - Why is an order of alpha imposed on the Renyi divergence?
Ans: This is done because the alpha-Renyi divergence is a restricted f-divergence and is related to the actual Renyi divergence through a closed form equation[3].

- What properties of restricted divergences limit us to using them for differential privacy?

Q - [6] proposes that all definitions of privacy satisfy convexity, post-processing and graceful composition. Is the conventional definition of Dwork et al, satisfy convexity? Check it out.
Ans: The proposed capacity bounded differential privacy satisfies all the three of them. The proof for post-processing invariance is a form of the
popular Data Processing Inequality applied to restricted divergences. 

The paper provides the exact and upper bounds on the privacy parameters for adversaries with linear class of functions with laplace, gaussian and matrix mechanisms.

## Questions<br>
1. Why only Renyi divergences? Why not use other forms of unrestricted divergences which are generalizations of KL-Divergence and the conventional definition of privacy loss? Check [5]


## References 
Computationally bounded DP:<br>
1. Ilya Mironov, Omkant Pandey, Omer Reingold, and Salil Vadhan. Computational differential privacy. In Proceedings of the 29th Annual International Cryptology Conference on Advances in Cryptology, CRYPTO ’09, pages 126–142, Berlin, Heidelberg, 2009. Springer-Verlag.
2. Adam Groce, Jonathan Katz, and Arkady Yerukhimovich. Limits of computational differential privacy in the client/server setting. In Proceedings of the 8th Conference on Theory of Cryptography, TCC’11, pages 417–431, 2011.

Renyi Divergence: <br>
3. Andrzej Cichocki and Shun-ichi Amari. Families of alpha- beta- and gamma- divergences: Flexible and robust measures of similarities. Entropy, 12(6):1532–1568, 2010
4. Ilya Mironov. Renyi differential privacy. In CSF Synposium, 2017.
5. Imre Csiszár. Information-type measures of difference of probability distributions and indirect observation. Studia Sci. Math. Hungary, 2:299–318, 1967.
