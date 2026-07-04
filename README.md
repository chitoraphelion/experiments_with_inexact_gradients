# Experiments with inexact gradients
This repository contains notebooks for experiments with inexact gradients in
\((L_0,L_1)\)-smooth optimization.

# Tools
The repository contains Jupyter notebooks for optimization experiments and
empirical motivation.

# a9a experiment
The file **a9a_inexact_gradients.ipynb** reproduces the logistic-regression
experiment with absolute gradient noise and the synthetic figures from
Appendix G.2.

# Floating-point error empirical estimation
The files **mnist_fp.ipynb**, **resnet_34_fp.ipynb**, and **mini_bert.ipynb**
estimate gradient errors caused by reduced floating-point precision.

# Smoothness empirical estimation
The files **mnist_smooth_est.ipynb**, **resnet_smooth_est.ipynb**, and
**mini_bert_smoothness.ipynb** estimate generalized smoothness constants on
standard machine-learning models.
