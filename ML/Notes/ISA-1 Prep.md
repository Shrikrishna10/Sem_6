https://chatgpt.com/canvas/shared/67b674c5e6ac8191a7989b608d9f095f #gpt

# **Machine Learning Study Guide**

## **Unit 1: Foundation of Machine Learning**

### **Key Topics:**

- Introduction to Classification and Regression **Classification and Regression** – _Chapter 1 (Pages 1-20)_
- Design and Analysis of Machine Learning Experiments**Design and Analysis of ML Experiments** – _Chapter 19 (Pages 547-575)_
    - Factors, Response, and Strategy of Experimentation
    - Response Surface Design, Randomization, Replication, and Blocking
- Guidelines for Machine Learning Experiments 
- Cross-Validation and Resampling Methods **Cross-Validation & Resampling Methods** – _Chapter 19.6 (Pages 559-560)_
- Measuring Classifier Performance **Measuring Classifier Performance** – _Chapter 19.7 (Pages 561-564)_
- Interval Estimation **Interval Estimation** – _Chapter 19.8 (Pages 565-568)_
- Hypothesis Testing **Hypothesis Testing** – _Chapter 19.9 (Pages 569-571)_

### **Study Tips:**

- Understand the basic differences between classification and regression.
- Learn different strategies for designing ML experiments.
- Focus on the importance of cross-validation techniques.
- Practice hypothesis testing and interval estimation problems.

### **Practice Questions:**

#### **Subjective Questions (4 marks each)**

1. Explain the key differences between classification and regression with examples.
2. Discuss various cross-validation techniques and their importance in ML experiments.
3. How does randomization and replication contribute to robust ML experiments?
4. Describe the steps involved in hypothesis testing in the context of ML.
#### **Mathematical Problems:**

1. Given a dataset of points \( (x_i, y_i) \), fit a simple linear regression model and compute the least squares estimates.
   
2. Compute precision, recall, and F1-score for a confusion matrix:
    
    ||Predicted Positive|Predicted Negative|
    |---|---|---|
    |Actual Positive|50|10|
    |Actual Negative|5|35|
    
3. Perform a hypothesis test for a given classifier accuracy of 85% with a sample size of 1000 instances.
   
4. Implement 5-fold cross-validation manually on a small dataset and compute the average accuracy.


#### **MCQs (2 marks each)**

1. What is the purpose of response surface design?
2. Which of the following is NOT a resampling method?
3. What metric is commonly used to measure classifier performance?
4. Which statistical concept is essential for confidence interval estimation?

#### **MCQs (1 mark each)**

1. Cross-validation helps in ______.
2. Which of the following is a method to prevent overfitting?
3. Hypothesis testing is used for ______.
4. The primary goal of blocking in ML experiments is ______.
5. Replication in ML experiments helps to ______.
6. What is a key advantage of randomization in experiments?
7. Which method is best for estimating model performance on unseen data?
8. A confusion matrix is used for evaluating ______.
9. The variance in a model is reduced by ______.
10. Mean squared error is used to measure performance in ______ problems.
11. The purpose of interval estimation is to ______.
12. Cross-validation is primarily used for ______.
13. Overfitting occurs when a model ______.
14. Which technique is used to improve model generalization?
15. A hypothesis test is considered significant if ______.
16. Bootstrapping is an example of ______.

---

## **Unit 2: Supervised Learning - Parametric Methods**

### **Key Topics:**

- Learning a Class from Examples 
- Vapnik-Chervonenkis Dimension **Vapnik-Chervonenkis (VC) Dimension** – _Chapter 4 (Pages 83-88)_
- Probably Approximately Correct (PAC) Learning **Probably Approximately Correct (PAC) Learning** – _Chapter 4.5 (Pages 88-92)_
- Noise in Learning 
- Learning Multiple Classes
- Regression Models
- Model Selection and Generalization
- Dimensions of a Supervised ML Algorithm
- Parametric Classification and Regression
- Tuning Model Complexity
    - Bias/Variance Dilemma **Bias-Variance Dilemma** – _Chapter 6.5 (Pages 139-142)_
    - Model Selection Procedures
- Gradient Descent and Logistic Discrimination **Gradient Descent & Logistic Regression** – _Chapter 11.2 (Pages 281-286)_
- Multivariate Data and Estimation **Multivariate Data & Estimation** – _Chapter 6.4 (Pages 136-139)_
- Handling Missing Values **Handling Missing Values** – _Chapter 6.6 (Pages 142-143)_
- Multivariate Normal Distribution and Classification **Multivariate Normal Distribution** – _Chapter 6.3 (Pages 131-136)_
- Tuning Complexity in Discrete Features **Tuning Model Complexity** – _Chapter 6.7 (Pages 143-146)_
- Multivariate Regression **Multivariate Regression** – _Chapter 6.8 (Pages 146-150)_

### **Study Tips:**

- Master the concepts of supervised learning and model selection.
- Understand the trade-offs in the bias-variance dilemma.
- Practice implementing gradient descent and logistic regression.
- Focus on handling multivariate data and missing values.

### **Practice Questions:**

#### **Subjective Questions (4 marks each)**

1. Explain PAC learning and its significance in supervised learning.
2. Discuss the role of the Vapnik-Chervonenkis dimension in machine learning.
3. What is the bias-variance dilemma? How can it be managed?
4. Explain the gradient descent algorithm and its application in ML.

#### **Mathematical Problems:**

1. Compute the Vapnik-Chervonenkis (VC) dimension for a perceptron classifier.
2. Given a dataset, apply gradient descent to optimize the loss function for logistic regression.
3. Estimate missing values in a multivariate dataset using mean imputation and compare with regression imputation.
4. Compute the Mahalanobis distance for a given dataset and analyze its use in multivariate normal distributions.

#### **MCQs (2 marks each)**

5. What is the main goal of model selection?
6. Which of the following affects the Vapnik-Chervonenkis dimension?
7. What type of learning does PAC learning belong to?
8. Which optimization algorithm is widely used in ML?

#### **MCQs (1 mark each)**

9. Gradient descent is used to minimize ______.
10. Logistic regression is primarily used for ______.
11. The bias-variance trade-off is important for ______.
12. In supervised learning, labels are ______.
13. Model generalization refers to ______.
14. The purpose of tuning model complexity is ______.
15. The learning rate in gradient descent controls ______.
16. Missing values in ML datasets can be handled by ______.
17. The normal distribution is essential for ______.
18. Classification problems involve predicting ______.
19. The term 'parametric' in ML refers to ______.
20. Overfitting can be reduced by ______.
21. Logistic regression uses ______ to model probabilities.
22. The main assumption in multivariate regression is ______.
23. Model selection procedures aim to ______.
24. The primary goal of PAC learning is ______.

---