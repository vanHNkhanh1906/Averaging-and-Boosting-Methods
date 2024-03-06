### Tools & libraries : 
- Python, Jupyter, pandas, scikit-learn, numpy, timeit

### DATASETS : 
- [Cars Data](https://www.kaggle.com/abineshkumark/carsdata) (classification).
### INTRODUCTION

- **Ensemble methods** aim to improve **generalizability** and **robustness** of an algorithm (single estimator) by combining the predictions of several base estimators [1,2]. 
- **The estimators** are built with a given Machine Learning algorithm.s, e.g: Decision Tree like CART and ID3, etc.
- To acheive this there are two general methods
  - (1) Averaging : 
      - Principle : Build several estimators independently and then to **Average** their predictions. 
      - Usually, The combined estimator is better than any of the single base estimator because its variance is reduced.
      - e.g., Bagging methods, Forests of randomized trees, etc.
  - (2) Boosting :
      - Principle : Weak Estimators are built sequentially, with each estimator attempting to reduce the bias of the predecessor (the combined estimator).
      - The weak learners often only have a slight performance advantage over random guessing.
      - The motivation is to combine several weak models to produce a powerful ensemble.
      - By focusing on training samples that are hard to classify, the overall performance of the ensemble is improved.
      - Boosting can lead to a decrease in bias and variance, but algorithms such as AdaBoost are also known for overfitting to the training data (high variance)
      - e.g., AdaBoost, Gradient Tree Boosting, etc.
      
 
