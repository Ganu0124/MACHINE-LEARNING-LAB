# Machine Learning Viva Questions and Answers

# Data Preprocessing

### 1. What is data preprocessing?

Data preprocessing is the process of cleaning, transforming, and organizing raw data before applying machine learning algorithms.

### 2. Why is data preprocessing important in machine learning?

It improves data quality, reduces noise, and increases model accuracy.

### 3. What are missing values?

Missing values are data entries that are unavailable or not recorded.

### 4. What are different techniques for handling missing values?

Deletion, mean imputation, median imputation, and mode imputation.

### 5. What is data cleaning?

Data cleaning removes errors, duplicates, and inconsistencies from data.

### 6. What is feature scaling?

Feature scaling transforms features into a common range.

### 7. What is normalization?

Normalization scales data between 0 and 1.

### 8. What is standardization?

Standardization transforms data to have mean 0 and standard deviation 1.

### 9. What is feature selection?

Selecting the most important features for model training.

### 10. What is feature extraction?

Creating new features from existing features.

### 11. What is label encoding?

Converting categorical values into numerical labels.

### 12. What is one-hot encoding?

Representing categories using binary columns.

### 13. What are outliers?

Data points that differ significantly from other observations.

### 14. How can outliers affect machine learning models?

They can reduce accuracy and distort predictions.

### 15. Why is train-test splitting necessary?

To evaluate model performance on unseen data.

---

# Linear Regression

### 1. What is Linear Regression?

A supervised learning algorithm used to predict continuous values.

### 2. What is the objective of Linear Regression?

To find the best-fit line that minimizes prediction error.

### 3. What is a dependent variable?

The output variable being predicted.

### 4. What is an independent variable?

The input variable used for prediction.

### 5. What is the regression line?

The best-fit line representing the relationship between variables.

### 6. What is the slope in Linear Regression?

The rate of change of the dependent variable with respect to the independent variable.

### 7. What is the intercept?

The value where the regression line crosses the y-axis.

### 8. What is prediction in Linear Regression?

Estimating future values using a trained model.

### 9. What is Mean Squared Error (MSE)?

The average squared difference between actual and predicted values.

### 10. What is Root Mean Squared Error (RMSE)?

The square root of MSE.

### 11. What is R² Score?

A metric that measures how well the model fits the data.

### 12. What is overfitting?

When a model learns training data too closely and performs poorly on new data.

### 13. What is underfitting?

When a model fails to learn important patterns from data.

### 14. What are the assumptions of Linear Regression?

Linearity, independence, homoscedasticity, and normality.

### 15. Give real-world applications of Linear Regression.

House price prediction, sales forecasting, and stock trend analysis.

---

# Logistic Regression

### 1. What is Logistic Regression?

A supervised classification algorithm used for categorical prediction.

### 2. Why is Logistic Regression used for classification?

Because it predicts probabilities between 0 and 1.

### 3. What is binary classification?

Classification involving two classes.

### 4. What is multiclass classification?

Classification involving more than two classes.

### 5. What is the sigmoid function?

A function that converts values into probabilities.

### 6. What is a decision boundary?

A boundary separating different classes.

### 7. What is probability estimation?

Calculating the likelihood of a class occurrence.

### 8. What is log-odds?

The logarithm of the odds of an event occurring.

### 9. What are the assumptions of Logistic Regression?

Independent observations and linearity between predictors and log odds.

### 10. What is maximum likelihood estimation?

A method used to estimate model parameters.

### 11. What is classification accuracy?

The percentage of correct predictions.

### 12. What is a confusion matrix?

A table used to evaluate classification performance.

### 13. What is precision?

The ratio of correctly predicted positive observations.

### 14. What is recall?

The ratio of actual positives correctly identified.

### 15. What are the applications of Logistic Regression?

Spam detection, disease prediction, and customer churn prediction.

---

# k-Nearest Neighbors (k-NN)

### 1. What is k-NN?

A supervised learning algorithm that classifies data based on nearest neighbors.

### 2. Why is k-NN called a lazy learner?

Because it stores training data and performs computation during prediction.

### 3. What does K represent?

The number of nearest neighbors used for prediction.

### 4. What is a distance metric?

A method used to measure similarity between data points.

### 5. What is Euclidean distance?

The straight-line distance between two points.

### 6. What is Manhattan distance?

The sum of absolute differences between coordinates.

### 7. How is classification performed in k-NN?

Using majority voting among nearest neighbors.

### 8. How is regression performed in k-NN?

By averaging the values of nearest neighbors.

### 9. How do you choose the value of K?

Using experimentation and validation techniques.

### 10. Why is feature scaling important in k-NN?

Because distance calculations depend on feature magnitude.

### 11. What are the advantages of k-NN?

Simple, easy to implement, and effective for small datasets.

### 12. What are the disadvantages of k-NN?

High memory usage and slow prediction for large datasets.

### 13. What is nearest neighbor search?

Finding the closest data points to a query point.

### 14. What is majority voting?

Assigning the class that appears most frequently among neighbors.

### 15. What are the applications of k-NN?

Recommendation systems, pattern recognition, and image classification.

# Decision Tree

### 1. What is a Decision Tree?

A Decision Tree is a supervised learning algorithm used for classification and regression tasks.

### 2. What is a root node?

The topmost node of the tree from which all branches originate.

### 3. What is a leaf node?

The final node that provides the prediction or decision.

### 4. What is a branch?

A connection between nodes representing a decision rule.

### 5. What is entropy?

Entropy measures the impurity or randomness in a dataset.

### 6. What is information gain?

Information gain measures the reduction in entropy after splitting data.

### 7. What is the Gini Index?

A metric used to measure the impurity of a node.

### 8. How does a Decision Tree choose the best split?

By selecting the feature with the highest information gain or lowest Gini Index.

### 9. What is tree pruning?

The process of removing unnecessary branches to reduce overfitting.

### 10. What is overfitting in Decision Trees?

When the tree memorizes training data and performs poorly on unseen data.

### 11. What is underfitting in Decision Trees?

When the tree is too simple to capture patterns in the data.

### 12. What are the advantages of Decision Trees?

Easy to understand, visualize, and interpret.

### 13. What are the disadvantages of Decision Trees?

Prone to overfitting and sensitive to small data changes.

### 14. What is a decision boundary?

A boundary that separates different classes in the feature space.

### 15. What are the applications of Decision Trees?

Medical diagnosis, fraud detection, and loan approval systems.

---

# Naive Bayes

### 1. What is Naive Bayes?

A probabilistic classification algorithm based on Bayes Theorem.

### 2. Why is it called "Naive" Bayes?

Because it assumes all features are independent.

### 3. What is Bayes Theorem?

A theorem used to calculate conditional probabilities.

### 4. What is prior probability?

The probability of an event before observing evidence.

### 5. What is posterior probability?

The probability of an event after observing evidence.

### 6. What is likelihood?

The probability of observing data given a class.

### 7. What is conditional probability?

The probability of an event occurring given another event.

### 8. What are the assumptions of Naive Bayes?

All features are conditionally independent.

### 9. What is Gaussian Naive Bayes?

A Naive Bayes variant used for continuous data following a normal distribution.

### 10. What is Multinomial Naive Bayes?

A variant commonly used for text classification and count data.

### 11. What is Bernoulli Naive Bayes?

A variant used for binary feature data.

### 12. What are the advantages of Naive Bayes?

Fast, simple, and effective for large datasets.

### 13. What are the disadvantages of Naive Bayes?

The independence assumption is often unrealistic.

### 14. Why is Naive Bayes used in text classification?

Because it works efficiently with high-dimensional text data.

### 15. What are the applications of Naive Bayes?

Spam filtering, sentiment analysis, and document classification.

---

# Support Vector Machine (SVM)

### 1. What is Support Vector Machine?

A supervised learning algorithm used for classification and regression.

### 2. What is a hyperplane?

A decision boundary that separates classes.

### 3. What are support vectors?

The data points closest to the hyperplane.

### 4. What is the margin in SVM?

The distance between the hyperplane and support vectors.

### 5. What is a kernel function?

A function used to transform data into higher dimensions.

### 6. What is a linear kernel?

A kernel used when data is linearly separable.

### 7. What is an RBF kernel?

A kernel used for non-linear classification problems.

### 8. What is a polynomial kernel?

A kernel that creates polynomial decision boundaries.

### 9. Why is feature scaling important in SVM?

Because SVM relies on distance calculations.

### 10. What is a soft margin?

A margin that allows some classification errors.

### 11. What is a hard margin?

A margin that does not allow any classification errors.

### 12. What are the advantages of SVM?

High accuracy and effective in high-dimensional spaces.

### 13. What are the disadvantages of SVM?

Slow training on large datasets.

### 14. What is kernel trick?

A technique that applies kernels without explicit transformation.

### 15. What are the applications of SVM?

Image classification, handwriting recognition, and bioinformatics.

---

# Ensemble Learning (Bagging)

### 1. What is Ensemble Learning?

A technique that combines multiple models to improve performance.

### 2. What is Bagging?

Bootstrap Aggregating, a method that trains multiple models on random samples.

### 3. What is Bootstrap Sampling?

Sampling with replacement from the training dataset.

### 4. What is a base learner?

The individual model used within an ensemble.

### 5. How does Bagging work?

It trains multiple models and combines their predictions.

### 6. Why does Bagging reduce variance?

Because averaging multiple models reduces prediction fluctuations.

### 7. What is majority voting?

Selecting the class predicted by most models.

### 8. What is Random Forest?

An ensemble of multiple Decision Trees using Bagging.

### 9. What is Boosting?

An ensemble technique that sequentially improves weak learners.

### 10. Difference between Bagging and Boosting?

Bagging trains models independently, while Boosting trains sequentially.

### 11. What are weak learners?

Models that perform slightly better than random guessing.

### 12. What are strong learners?

Models with high predictive accuracy.

### 13. What are the advantages of Bagging?

Reduces overfitting and improves stability.

### 14. What are the disadvantages of Bagging?

Requires more computational resources.

### 15. What are the applications of Ensemble Learning?

Fraud detection, recommendation systems, and medical diagnosis.
# Neural Network and Backpropagation

### 1. What is an Artificial Neural Network (ANN)?

An ANN is a machine learning model inspired by the structure and functioning of the human brain.

### 2. What is a neuron?

A neuron is the basic processing unit of a neural network that receives inputs and produces an output.

### 3. What is an input layer?

The first layer of a neural network that receives input data.

### 4. What is a hidden layer?

An intermediate layer that performs computations and feature extraction.

### 5. What is an output layer?

The final layer that produces the prediction result.

### 6. What is an activation function?

A function that determines whether a neuron should be activated.

### 7. What is ReLU?

Rectified Linear Unit, an activation function defined as max(0,x).

### 8. What is Sigmoid activation?

An activation function that converts values into probabilities between 0 and 1.

### 9. What is Softmax activation?

An activation function used for multiclass classification problems.

### 10. What is forward propagation?

The process of passing input data through the network to generate predictions.

### 11. What is backpropagation?

The process of updating network weights by propagating errors backward.

### 12. What is an epoch?

One complete pass through the entire training dataset.

### 13. What is a loss function?

A function that measures prediction error.

### 14. What is gradient descent?

An optimization algorithm used to minimize the loss function.

### 15. What are the applications of Neural Networks?

Image recognition, speech recognition, NLP, and medical diagnosis.

---

# Model Evaluation Metrics

### 1. What is model evaluation?

The process of measuring the performance of a machine learning model.

### 2. What is accuracy?

The ratio of correctly predicted observations to total observations.

### 3. What is precision?

The ratio of correctly predicted positive observations to total predicted positives.

### 4. What is recall?

The ratio of correctly predicted positive observations to all actual positives.

### 5. What is F1-Score?

The harmonic mean of precision and recall.

### 6. What is a confusion matrix?

A table used to evaluate classification performance.

### 7. What is a true positive (TP)?

A positive instance correctly classified as positive.

### 8. What is a true negative (TN)?

A negative instance correctly classified as negative.

### 9. What is a false positive (FP)?

A negative instance incorrectly classified as positive.

### 10. What is a false negative (FN)?

A positive instance incorrectly classified as negative.

### 11. What is ROC Curve?

A graph showing the relationship between True Positive Rate and False Positive Rate.

### 12. What is AUC Score?

Area Under the ROC Curve, measuring classifier performance.

### 13. What is cross-validation?

A technique that evaluates a model using multiple train-test splits.

### 14. Why is model evaluation important?

To determine how well a model performs on unseen data.

### 15. What are the limitations of accuracy?

Accuracy may be misleading for imbalanced datasets.

---

# k-Means Clustering

### 1. What is clustering?

The process of grouping similar data points together.

### 2. What is k-Means Clustering?

An unsupervised learning algorithm that partitions data into K clusters.

### 3. What is unsupervised learning?

Learning from unlabeled data.

### 4. What is a centroid?

The center point of a cluster.

### 5. How does k-Means work?

It assigns points to the nearest centroid and updates centroids iteratively.

### 6. What is WCSS?

Within Cluster Sum of Squares, a measure of cluster compactness.

### 7. What is inertia?

The sum of squared distances between data points and their centroids.

### 8. What is the Elbow Method?

A technique used to determine the optimal number of clusters.

### 9. How is the value of K selected?

Using methods such as the Elbow Method.

### 10. Why is feature scaling important in k-Means?

Because clustering is based on distance calculations.

### 11. What are the advantages of k-Means?

Simple, fast, and easy to implement.

### 12. What are the disadvantages of k-Means?

Requires predefined K and is sensitive to outliers.

### 13. What is cluster assignment?

Assigning a data point to its nearest centroid.

### 14. What is cluster convergence?

The stage where centroids stop changing significantly.

### 15. What are the applications of k-Means?

Customer segmentation, image compression, and market analysis.

---

# DBSCAN Clustering

### 1. What is DBSCAN?

A density-based clustering algorithm used to identify clusters and outliers.

### 2. What is density-based clustering?

Clustering based on regions with high point density.

### 3. What does DBSCAN stand for?

Density-Based Spatial Clustering of Applications with Noise.

### 4. What is epsilon (eps)?

The maximum distance between neighboring points.

### 5. What is min_samples?

The minimum number of points required to form a dense region.

### 6. What is a core point?

A point with at least min_samples neighbors within eps distance.

### 7. What is a border point?

A point near a core point but with fewer neighbors.

### 8. What is a noise point?

A point that does not belong to any cluster.

### 9. How does DBSCAN identify clusters?

By connecting neighboring core points and their border points.

### 10. Why does DBSCAN not require K?

Because it automatically discovers the number of clusters.

### 11. What are outliers in DBSCAN?

Noise points that do not belong to any cluster.

### 12. What are the advantages of DBSCAN?

Detects arbitrary-shaped clusters and identifies outliers.

### 13. What are the disadvantages of DBSCAN?

Sensitive to eps and min_samples values.

### 14. Difference between DBSCAN and k-Means?

DBSCAN is density-based and detects outliers, while k-Means uses centroids and requires K.

### 15. What are the applications of DBSCAN?

Anomaly detection, geographic analysis, and fraud detection.

---

# Most Important Viva Questions Frequently Asked 

1. Difference between Supervised and Unsupervised Learning?
2. Difference between Classification and Regression?
3. Difference between Overfitting and Underfitting?
4. Difference between Bagging and Boosting?
5. Difference between k-Means and DBSCAN?
6. Difference between Entropy and Gini Index?
7. Difference between Precision and Recall?
8. Difference between Accuracy and F1-Score?
9. Why is Feature Scaling important?
10. Why do we split data into Train and Test sets?
11. What is Cross Validation?
12. What is Hyperparameter Tuning?
13. What is Bias and Variance?
14. Why is Random Forest better than a single Decision Tree?
15. Why is Logistic Regression used for Classification?

