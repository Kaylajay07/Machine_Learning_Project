# Machine_Learning_Project
Project Summary: Predicting Student Dropout Rates and Academic Success
This project aims to predict student dropout rates and academic success using machine learning models. The dataset used for this project is sourced from the UC Irvine Machine Learning Repository. It includes comprehensive information available at the time of student enrollment, encompassing academic paths, demographic characteristics, socio-economic backgrounds, and academic performance at the conclusion of the first and second semesters.

Dataset Overview
The dataset provides rich information on:

Academic Path: Courses taken, majors chosen, and academic plans.
Demographic Characteristics: Age, gender, ethnicity, and other personal attributes.
Socio-Economic Background: Family income, parental education levels, and financial aid status.
Academic Performance: Grades and academic standing at the end of the first and second semesters.
Models Developed
To predict student dropout rates and academic success, we developed and evaluated three different machine learning models:

Logistic Regression Model

Purpose: To provide a simple yet effective baseline model for classification.
Performance Evaluation: A confusion matrix was generated to evaluate the model's performance.
Results: Provided insight into the classification accuracy and the distribution of true positives, false positives, true negatives, and false negatives.
Random Forest Model

Purpose: To leverage the ensemble learning approach for improved accuracy and to gain insights into feature importance.
Performance Evaluation: Offered higher accuracy and detailed feature importance metrics, helping us understand which factors most significantly impact student outcomes.
Results: Achieved an overall accuracy of 78%, with the highest performance in predicting students who would graduate.
K-Means Clustering with PCA

Purpose: To identify natural clusters in the dataset and improve clustering efficiency using Principal Component Analysis (PCA).
Approach: Applied PCA to reduce dimensionality before performing K-means clustering.
Results: Enhanced the clustering process by simplifying the data structure, allowing for clearer identification of distinct student groups.
Key Findings
The Logistic Regression Model provided a straightforward baseline with reasonable accuracy, but it lacked the depth of insights offered by more complex models.
The Random Forest Model not only matched the accuracy of other models but also provided valuable feature importance metrics, making it the most informative model regarding which features most strongly influence student outcomes.
Applying PCA before the K-means algorithm improved the clustering process, highlighting distinct groups within the student population that can be targeted for specific interventions.
Conclusion
The dataset from the UC Irvine Machine Learning Repository proved to be a robust foundation for developing predictive models for student dropout rates and academic success. Among the models developed, the Random Forest Model stood out for its accuracy and the depth of insights it provided. Using PCA enhanced the efficiency of the K-means clustering algorithm, demonstrating the value of dimensionality reduction in unsupervised learning tasks. These models can significantly aid educational institutions in identifying at-risk students early and implementing targeted interventions to improve student retention and success.
