This folder contains the distributed implementation of the System Identification Algorithm which can be found for the "vanilla" version. The distributed implementation is based on the following paper

Boyd, Stephen, et al. "Distributed optimization and statistical learning via the alternating direction method of multipliers." Foundations and Trends in Machine Learning 3.1 (2011): 1-122.

==================== Quick Guide to Start ===========================

1. Download CVX toolbox from www.cvxr.com and run 'cvx_setup.m' to install the toolbox.
2. Run 'start_up.m' to the toolbox to your directory
3. RUN 'RUN_DistriID.m' and have fun!

============ Guidience on the Use of Parallel Computing Toolbox in Matlab =============== 

In Matlab 2015a, use     
parpool(numberofcluster); or delete(gcp);
to start or delete multicluster

In previous version, check it on MathWorks Website, typically, use matlabpool(numberofcluster)

=============== Acknowledgement ===============

1. The four files in folder 'inf' are implenmted by Dr Hannes Nickisch
http://hannes.nickisch.org/
http://hannes.nickisch.org/code/glm-ie/doc/index.html

2. dwl1.m and wl1.m are implmemetated based on 
http://web.stanford.edu/~boyd/papers/admm/lasso/lasso.html
and 
http://web.stanford.edu/~boyd/papers/admm/group_lasso/group_lasso_feat_split.html



