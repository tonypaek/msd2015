regression
==

intro: the name

# within machine learning

- UL (x)
    - explain
- SL (y|x) 
  + classificatin
  + regression
    - predict, explain
- RL (y|x,a)
    - predict, explain, control

regression is gateway

# old school Regression

- loss=OSS/SSL
- optimization=OLS
  - model known, e.g., dropping rock
  - go through model
  - linear algebra
    + projection
    + inversion
  - interpreting results

# as probability

- why is error called 'chi-squared'?
- as probability
- maximim likelihood

# when to stop fitting?

## as generative model
 
- bayesianism
- additive regularizers as MAP instead of MLE

## who cares? what works?

- log posterior is a convex loss in data plus a regularizer
- generic form

# let's code

- fake data
- covariates: scale them and see what happens to coefficients
- covariates: add some noise
- covariates: add some linearly dependent ones
- real data: neilsen 
- add some polynomaisl
- do cv.glmnet examples

# optimization

- gradient descent
- stochastic gradient descent
- connect with parallelism