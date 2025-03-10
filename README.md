# Machine-Learning-Models-Showcase

This repository features a diverse collection of machine learning models, including both supervised and unsupervised techniques. Inside you'll find detailed Jupyter notebooks and code examples that demonstrate various approaches to classification, regression, clustering, and more. 

### Binomial, Multinomial Regression

The notebook demonstrates two distinct approaches to classification. For binary (binomial) classification, models such as logistic regression are applied to distinguish between two classes by estimating probabilities and establishing decision boundaries. In contrast, for multiclass (multinomial) classification, the notebook extends these techniques—often via multinomial logistic regression or comparable algorithms—to handle three or more classes, enabling the simultaneous prediction of multiple outcomes. The notebook also details performance evaluation through metrics like accuracy and confusion matrices, providing insights into each model's strengths and limitations as they are applied to real-world data .

### Logistic Regression, Elastic Net
The notebook demonstrates a modeling approach that integrates logistic regression with elastic net regularization. Logistic regression serves as a foundational method for binary classification by estimating probabilities through a logistic function, while elastic net combines the strengths of both L1 and L2 regularization to control overfitting and handle multicollinearity. This combination not only improves the model's predictive performance in high-dimensional settings but also enhances interpretability by promoting a balance between feature selection and coefficient shrinkage .

### Decision trees, bagging random forest 
This notebook explores tree-based ensemble methods. It begins with decision trees, which serve as a foundational algorithm for both classification and regression by splitting data into homogenous subsets. The notebook then delves into bagging (Bootstrap Aggregating), where multiple decision trees are built on different subsets of data to reduce variance. Finally, it introduces random forests, an extension of bagging that injects randomness in feature selection to further enhance predictive accuracy and robustness. This ensemble approach provides a powerful alternative to single decision trees by combining multiple models to improve overall performance .

### Gradient Boosting Classifier, Gradient Boosting Regressor
The "Gradient Boosting Classifier, Gradient Boosting Regressor.ipynb" notebook demonstrates the application of gradient boosting techniques for both classification and regression. Gradient boosting builds a strong predictive model by iteratively combining multiple weak learners—typically decision trees—in a sequential manner. In the classification context, the Gradient Boosting Classifier enhances prediction accuracy by focusing on and correcting previous misclassifications, while the Gradient Boosting Regressor refines continuous predictions through similar iterative improvements. The notebook offers insights into model training, hyperparameter tuning, and performance evaluation, showcasing the power and flexibility of gradient boosting in handling complex datasets .

### Support Vector Classifier
The "Support Vector Classifier.ipynb" notebook demonstrates the use of support vector machines for classification tasks. It focuses on the Support Vector Classifier (SVC), which works by identifying the optimal hyperplane that maximizes the margin between different classes. The notebook also explores the use of kernel functions to capture non-linear relationships, showcasing how SVC can be adapted to handle complex datasets. Key steps such as data preprocessing, model training, hyperparameter tuning, and performance evaluation are covered to illustrate the practical application of SVC .


### Gaussian Mixture, DBSCAN and K-means
The "Gaussian Mixture, DBSCAN and K-means" notebook explores unsupervised clustering techniques using Gaussian Mixture Models, DBSCAN, and K-means. Gaussian Mixture Models offer a probabilistic approach by modeling the data as a mixture of several Gaussian distributions, allowing for soft assignments of data points to clusters. DBSCAN identifies clusters based on data density and is particularly effective at detecting outliers. Meanwhile, K-means clustering partitions data into a predetermined number of clusters by minimizing within-cluster variance. This notebook provides a hands-on demonstration of these methods, illustrating their applications in uncovering hidden structures within datasets .







