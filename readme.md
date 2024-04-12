This anonymized repository contains some experiment figures and tables for **Ranking with Slot Constraints** KDD submission.

We repeat the real-world benchmarks (Table 2 in the paper) and college admission experiments (Table 3 in the paper) for 3 runs and report the results in the format of "mean $\pm$ std" (for standard error we will divide the std by $\sqrt{3}$) in ``table_2.md`` and ``table_3.md``.

``Sec 4.2 real-world benchmarks`` contains figures of number of filled slots versus ranking shortlist size in real-world benchmarks as shown in subsection 4.2. For each figure, the left subfigure would show the empirical optimization objectives of MatchRank $\hat{M}(X_k) = \dfrac{1}{n} \sum_{j = 1}^n \text{MBM}(X_k, \mathcal{S} | R_j)$ versus ranking shortlist size $k$. The right subfigure would show the number of filled slots with relevant candidates $M(X_k) = \text{MBM}(X_k, \mathcal{S} | R)$, when ground-truth relevances $R$ are revealed during the evaluation phase. 

``Sec 4.3 college admission dataset`` contains figures of number of filled slots versus ranking shortlist size in the college admission dataset as shown in subsection 4.3.

Notice that each curve in ``Sec 4.2 real-world benchmarks`` and ``Sec 4.3 college admission dataset`` only represents a single run (one random seed). 