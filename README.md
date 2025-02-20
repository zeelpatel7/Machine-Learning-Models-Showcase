# Machine-Learning-Models-Showcase

This repository features a diverse collection of machine learning models, including both supervised and unsupervised techniques. Inside you'll find detailed Jupyter notebooks and code examples that demonstrate various approaches to classification, regression, clustering, and more. 

### Binomial, Multinomial Regression

The notebook demonstrates two distinct approaches to classification. For binary (binomial) classification, models such as logistic regression are applied to distinguish between two classes by estimating probabilities and establishing decision boundaries. In contrast, for multiclass (multinomial) classification, the notebook extends these techniques—often via multinomial logistic regression or comparable algorithms—to handle three or more classes, enabling the simultaneous prediction of multiple outcomes. The notebook also details performance evaluation through metrics like accuracy and confusion matrices, providing insights into each model's strengths and limitations as they are applied to real-world data .

### Logistic Regression, Elastic Net
The notebook demonstrates a modeling approach that integrates logistic regression with elastic net regularization. Logistic regression serves as a foundational method for binary classification by estimating probabilities through a logistic function, while elastic net combines the strengths of both L1 and L2 regularization to control overfitting and handle multicollinearity. This combination not only improves the model's predictive performance in high-dimensional settings but also enhances interpretability by promoting a balance between feature selection and coefficient shrinkage .

### Decision trees, bagging random forest 
This notebook explores tree-based ensemble methods. It begins with decision trees, which serve as a foundational algorithm for both classification and regression by splitting data into homogenous subsets. The notebook then delves into bagging (Bootstrap Aggregating), where multiple decision trees are built on different subsets of data to reduce variance. Finally, it introduces random forests, an extension of bagging that injects randomness in feature selection to further enhance predictive accuracy and robustness. This ensemble approach provides a powerful alternative to single decision trees by combining multiple models to improve overall performance .
