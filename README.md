# Evaluation of Practical Contextual Bandit Algorithms
Scripts for evaluation of contextual bandit algorithms in [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit).
See the following paper for details:

A. Bietti, A. Agarwal, and J. Lanford. [Practical Evaluation and Optimization of Contextual Bandit Algorithms](https://arxiv.org/abs/1802.04064). arXiv preprint, 2018.

# OML

You will need an OML account to get the datasets.

1. create an account at openml.org and login
2. click icon at the top right once logged in
3. click api authentication button
4. create file config.py in this directory with contents 
```
OML_API_KEY="..."
VW_DS_DIR="..."
```
