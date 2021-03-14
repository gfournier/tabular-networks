# Notes on NODE paper

Paper link: https://arxiv.org/pdf/1909.06312.pdf

## Summary
State of the art for tabular data: gradient boosting decision trees / random forest.
Implementations: LightGBM, XgBoost, CatBoost
NODE is inspired by CatBoost = ensemble model on Oblivious Decision Trees

## Oblivious Decision Tree
![image](https://user-images.githubusercontent.com/5203595/111043285-ff8b6c00-8441-11eb-9058-bc974f724c94.png)
* Balanced decision tree
* at each level same feature split is used at each node
* d depth = 2^d leaves
* can be translated to a **decision table**
* weaker learner than a classic tree
* less prone to overfitting

## entmax
![image](https://user-images.githubusercontent.com/5203595/111043448-e1723b80-8442-11eb-8ac5-7949fa08a42b.png)
