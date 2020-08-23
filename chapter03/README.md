# Decision Tree

A **decision tree** is a tree-based decision support tool that uses a graph or model of decisions and their possible consequences, including chance event outcomes, resource costs, and utility. Tree based learning algorithms are considered to be one of the best and mostly used supervised learning methods.Decision Tree algorithms are referred to as **CART** **(Classification and Regression Trees)**.

***“The possible solutions to a given problem emerge as the leaves of a tree, each node representing a point of deliberation and decision.”\***

*- Niklaus Wirth (1934 — ), Programming language designer*

Example: To classify if a person is fit or unit?



![Related image](https://miro.medium.com/max/410/0*LHzDR-s89Ggfqn7p.png)

[1][https://medium.com/greyatom/decision-trees-a-simple-way-to-visualize-a-decision-dc506a403aeb#:~:text=A%20decision%20tree%20is%20a%20flowchart%2Dlike%20structure%20in%20which,taken%20after%20computing%20all%20attributes).](https://medium.com/greyatom/decision-trees-a-simple-way-to-visualize-a-decision-dc506a403aeb#)

A decision tree tries to solve problem using graph-tree approach. Each internal node in the tree respresent to an attribute, and each leaf node corresponds to a class label.

Advantages:

1. **Easy to Understand**:
2. **Useful in Data exploration**
3. **Little effort for data preparation**
4. Easy to generate rules

Disadvantages:

1. Over fitting
2. Not fit for continuous variables
3. variance of data can effect decision tree
4. can create biased tree if data is unbalanced.
5. can be large tree-pruning is necessary
6. does not easily handle non-numeric data

**Splitting of Decision tree**

1. Continuous Target Variable

   ​		Reduction in Variance

2. Categorical Target Variable

   - Gini Impurity
   - Information Gain
   - Chi-Square

Read more: https://www.analyticsvidhya.com/blog/2020/06/4-ways-split-decision-tree/

**Random Forest**



### Advantages & Disadvantages

**Advantages:**

- Typically have very good performance
- Remarkably good “out-of-the box” - very little tuning required
- Built-in validation set - don’t need to sacrifice data for extra validation
- No pre-processing required
- Robust to outliers

**Disadvantages:**

- Can become slow on large data sets
- Although accurate, often cannot compete with advanced boosting algorithms
- Less interpretable