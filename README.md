# NN-LMM
Data, scripts and results for NN-MM paper:

> Tianjing Zhao, Jian Zeng, Hao Cheng, Extend mixed models to multilayer neural networks for genomic prediction including intermediate omics data, Genetics, Volume 221, Issue 1, May 2022, iyac034, https://doi.org/10.1093/genetics/iyac034

Those files are:

* **Part1_NNLMM_vs_singlestep**: compare the prediction performance of NN-LMM to the single-step approach in [Christensenet al.(2021)](https://doi.org/10.1093/genetics/iyab130). (Figure 4 in NN-LMM paper)
* **Part2_NNLMM_nonlinear**: the prediction performance of NN-GBLUP with a linear function was compared to NN-GBLUP with a nonlinear sigmoid activation function, when the underlying relationship between intermediate omics features and phenotypes was nonlinear for the simulated datasets.  (Figure 5 in NN-LMM paper)
* **Part3_NNGBLUP_vs_NNBayesC**: performance of NN-LMM with a GBLUP prior (i.e, NN-GBLUP) and NN-LMM with a BayesC prior (i.e., NN-BayesC) were compared, and linear activation functions were applied. (Figure 6 in NN-LMM paper)


NN-MM is also called "mixed effects neural networks". To perform NN-MM in [JWAS](https://github.com/reworkhow/JWAS.jl), please see [documentation](https://reworkhow.github.io/JWAS.jl/latest/) and latest examples. The scripts here may be invalid due to the updated NN-MM interface in JWAS. 


#### Reference
*Christensen OF, Börner V, Varona L, Legarra A. Genetic evaluation including intermediate omics features. Genetics. 2021 Oct;219(2):iyab130.*
