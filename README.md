# Final Project for STAT 256 Causal Inference
## Replication Paper Choice
We choose to replicate Early Childhood Intervention and Life-Cycle Skill Development: Evidence from Head Start [David Deming, 2009]. Yes...we use Python...

## Code Explanation
```replicate.ipynb``` contains the Jupyter notebook for replicating Table 1-5 in the original paper; ```robustness.ipynb``` contains robustness checks and realasysis. The two notebooks should reporduce every table and figure in our writeup

## Data Source
The NLSY79 Child and Young Adult dataset is available at https://www.bls.gov/nls/getting-started/nlscya_all_1979-2018.zip. However, due to the large dataset size, our computer are not able to open the data. Instead, the author releases the uncleaned dataset (available at https://www.openicpsr.org/openicpsr/project/113563/version/V1/view), which is the relevant, renamed raw data for this study. 

## Exotic Packages
The Multivariate KS test library (mks_test) is cloned from https://github.com/o-laurent/multivariate-ks-test
