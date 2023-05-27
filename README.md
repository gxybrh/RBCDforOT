# RBCDforOT

This repository restores all the experiment data in the paper: Randomized methods for computing optimal transport without regularization and their convergence analysis

Experiment5_1.mlx is the matlab file generating the Figure 2 in Section 5.1.

Experiment5_2.mlx is the matalbe file generating Figure 3: Solving large-scale problem via ARBCD.

ExperimentF_xd.mlx is the matlab file generating the figures and tables in Appendix F related to Wasserstein distance between x dimension distributions.

RBCD0.mlx, reRBCD.mlx, ARBCD.mlx, SKstab.m, are the algorithms used in these experiments. The file names are strongly related to the algorithm names in the paper. In particular, SKstab is the stabelized Sinkhorn's algorithm.

round_matrix.m is a file implementing the rounding procedure in the paper: J. Altschuler, J. Niles-Weed, and P. Rigollet, Near-linear time approximation algorithms for optimal transport via Sinkhorn iteration, Advances in Neural Information Processing Systems, 30 (2017).

map_0.log records data of sample points from the empirical invariant measure.
