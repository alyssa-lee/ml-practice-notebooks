# Research log

## Week 1
First meeting with Caleb: Mon 9/12

Spent ~10 hours on the following tasks:
- K-means clustering and regression on toy datasets (k-means.ipynb, regression.ipynb)
- Read & take notes on [Varying-coefficient models paper](https://www.jstor.org/stable/pdf/2345993.pdf?refreqid=excelsior%3A05ef87b8271401c0f0609c6bfc2e39ef&ab_segments=&origin=&acceptTC=1)

Things I learned:
- K-means clustering
- Logistic regression classifiers
- numpy, pandas, matplotlib, scikit-learn
- Generalized varying-coefficients model

## Week 2
Meeting with Caleb: Mon 9/19

Tasks (9h):
- Read & take notes on [Estimating time-varying networks paper](https://arxiv.org/pdf/0812.5087.pdf) (3h)
- Brainstorm - when would clustering by context improve accuracy of linear regression models? (1h)
- Code - set up simulation, clustering, regression, and evaluation using "bad" example (2h)
- Code - try different "good" examples (2h)
- Reflection - write thoughts (1h)

Blockers:
- Reinstall VSCode, set up conda env, install Jupyter Notebook Renderers extension (solved)
- Bug: was using the wrong variable to predict clusters
- Confused about relationship of X and C

Things I learned:
- Markov random fields (hidden undirected Markov property graph generates observed data)
- Reviewed stats knowledge (maximum likelihood estimation)
- Regularization term (penalizes too many terms in the model)
- Kernel smoother (estimating a smooth function as a weighted average of observed data)
- Connection between time-varying networks and generalized varying-coefficient model (time is the contextual factor causing coefficients to vary)
- Writing reusable code in Jupyter notebooks
- NumPy vectorization (optimized, faster than loops)
- Practiced making matplotlib plots
- Jupyter notebook keyboard shortcuts
- When cluster models are helpful, and when they are not

## Week 3
Meeting with Caleb: Mon 9/26

Tasks:
- Use Contextualized.ML package to learn contextual model on examples from last week
- Read papers

Things I learned:
- Review prior/posterior distribution stuff