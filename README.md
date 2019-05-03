# Evaluation of Practical Contextual Bandit Algorithms
Scripts for evaluation of contextual bandit algorithms in [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit).
See the following paper for details:

A. Bietti, A. Agarwal, and J. Lanford. [Practical Evaluation and Optimization of Contextual Bandit Algorithms](https://arxiv.org/abs/1802.04064). arXiv preprint, 2018.

# obtaining data: `oml_to_vw.py`

You will need an OML account to get the datasets.

1. create an account at openml.org and login
2. click icon at the top right once logged in
3. click api authentication button
4. create file config.py in this directory with contents 
```
OML_API_KEY="..."
VW_DS_DIR="..."
```

# running the bakeoff: `run_vw_job.py`

* set up to facilitate parallelism
* first argument is `task_id`: should span from 0 to number-of-parallel-tasks
* second argument is `num_tasks`: number of parallel tasks
* `./run_vw_job.py 0 1` runs everything with no parallelism
