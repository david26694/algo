

**Content questions:**

* What is a balancing score?
* What's the mathematical definition of `do(T = 1)`? What event is it from a probability point of view, as a subset of the sample space?
* Why do the first and second sampling methods that estimate the effect of the treatment in the Rubin paper provide such different results?

**Other content comments:**

> As these are the first sessions, it would be good to define a common notation that we can take as a basis for all the sessions. Maybe together with a document/reference that explains the most basic concepts of Causal Inference.

**Applications of propensity scores and inverse probability weighting:**

* > Many of the surveys are not representative sample, so using the census data one can create the representative sample in Economics. In the industry, it would be interesting if one wants to attract underrepresented sample of customers.

* > Analysis of historical retail sales data to analyze which types of promotions work best according to other variables (type of customer, seasonality, type of product...):
    * Let's say we do more promotions on new customers than on returning customers, but the new customers spend less than the returning customers. A naive analysis would say that the more promotions we do, the less they spend. Using propensity scores or inverse probability weights might help solve this.

* To weigh the training samples in a supervised ML model. If the propensity scores (with respect to some test distribution) of a training instance is low, we might want to assign a lower weight to that training instance (of course a condition to use this is to have some test data when you train, possible examples are Kaggle or when validating in a time-series way).
