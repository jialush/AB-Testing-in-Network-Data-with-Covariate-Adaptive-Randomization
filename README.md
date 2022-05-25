# Introduction
 This repository contains the R codes for the numerical studies in " This repository contains the R codes used for the numerical studies in the paper "Adaptive A/B Test on Networks with Cluster Structures."

# Requirements
- R packages for randomization algorithm: "igraph", "matrixStats", "data.table", "reshape2", "dplyr".
- R package for R Plot: "ggplot2", "ggrepel", "viridis", "readr", "readxl".

# Code
## R code for randomization algorithm
- CAR2.rmd: R code for randomization algorithm under the hypothetical case with ten covariates.
- CAR10.rmd: R code for randomization algorithm under the hypothetical case with two covariates.
- Farmer.rmd: R code for randomization algorithm under real data.

## R code for R plots 
- Nips_Plot2_10.rmd: R code for plotting algorithm results, mean square error(mse), under the hypothetical case with ten covariates.
- Nips_Plot22.rmd: R code for plotting algorithm results, mean square error(mse), under the hypothetical case with two covariates.
- Nips_PlotReal_AT.rmd: R code for plotting algorithm results, mean square error(mse), under real data.

# Data
We redesign the experiment in paper Cai, J., Janvry, A. D., and Sadoulet, E. 2015. Social networks and the decision insure. American Economic Journal: Applied Economics, 7(2), 81-108. The paper studies the influence of the social network on insurance adoption by rice farmers in rural China. The authors publicly provide their data which can be accessed via this link: https://www.openicpsr.org/openicpsr/project/113593/version/V1/view.

We also perform data preprocessing and provide the cleaned data used for our real data simulations.

# Others
Simulations results and the plots used in the paper are in folder Result. 
