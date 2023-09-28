# mtp2-bbd
Matlab, Rm and Python implementations on how to use bridge-block decomposition to acclerate the learning of large-scale sparse MTP2 Gaussian graphical models proposed in [1]. 

The codes contain following procedures.

(1) Generating the data.
(2) Computing thresholded graph and bridge-block decomposition.
(3) Solving Sub-problems individually using FPN solver [2].
(4) Obtaining optimal solution using methods in [1].

Please skip first step if you have data matrix or sample covariance matrix provided. The methods could significantly accelerate the convergence of existing algroithms and reduce memory cost when the thresholded graphs are sparse. 

[1] Xiwen Wang, Jiaxi Ying, and Daniel P. Palomar, 'Learning Large-Scale MTP2 Gaussian Graphical Models via Bridge-Block Decomposition,' accepted in Neural Information Processing Systems (NeurIPS), New Orleans, LA, USA, Dec. 2023.

[2] J.-F. Cai, J. V. de Miranda Cardoso, D. P. Palomar, and J. Ying, "Fast Projected Newton-like Method for Precision Matrix Estimation under Total Positivity", accepted in Neural Information Processing Systems (NeurIPS), New Orleans, LA, USA, Dec. 2023.


