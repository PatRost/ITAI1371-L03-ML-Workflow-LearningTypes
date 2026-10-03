# ITAI 1371 - Module 3 Group Contribution Journal

## Group 4

This document contains the individual contributions of each group member for the Module 3 Machine Learning Workflow and Types of Learning lab.

---

## Member 1 - Patrick Rostand Gandjouon Tchassem
### Contribution Area: Data Exploration and EDA

My main contribution to this lab was working on the data exploration and Exploratory Data Analysis (EDA) part of the Wine dataset. I reviewed the dataset to understand what information we were working with before building the machine learning models.
I helped check the number of samples, features, and wine classes in the dataset. The dataset contained 178 samples, 13 features, and three wine classes. I also checked for missing values and confirmed that the dataset had no missing data.
I also worked on understanding the visualizations used during EDA. I reviewed the class distribution chart to see how the wine samples were divided between the three classes. I also looked at the correlation heatmap to understand how some of the features were related to each other.
My contribution helped me understand why we should not immediately start training a machine learning model when we receive a dataset. We first need to explore the data, check its quality, and understand what we are working with. This part of the lab helped me become more comfortable with the beginning stages of the machine learning workflow.


---

## Member 2 - [Saimi Manasiya]
Member 2 – Data Preparation & Splitting

For this lab, my assigned contribution was Data Preparation and Splitting.

I prepared the data for the modeling stage by identifying the appropriate input features (X) and target variable (y) from the Wine dataset. I reviewed the available variables and selected the initial features that would be used as inputs for the machine learning models.

I also created the 80/20 train-test split, using 80% of the dataset for training and 20% for testing. The training data is used by the model to learn patterns from the dataset, while the testing data is kept separate so that the model can be evaluated using data it has not seen during training.

I made sure that the feature data and target labels were separated correctly before the modeling stage. This prepared dataset was then available for the team members working on model training and evaluation.

My contribution helped establish the data preparation stage of the machine learning workflow and provided the properly organized training and testing data needed for the next steps of the lab.
---

## Member 3 - [Kenneth Kouokam]
### Contribution Area: Model Training and Evaluation

My contribution to Group 4 focused on Model Training and Evaluation, covering cells 13 through
15 of the notebook. I compared Logistic Regression and a Decision Tree using the same four wine
measurements and the existing split of 142 training samples and 36 test samples. In the initial
results, Logistic Regression achieved 88.9% accuracy, while the Decision Tree achieved 83.3%. I
explained what these scores meant and how testing on held-out examples helps assess a model's
ability to classify new data.

I also examined precision, recall, and F1-score in the classification reports and interpreted the
confusion matrix to identify which wine classes were confused. This added detail beyond the
overall accuracy and helped explain the models' mistakes. I included a limitation of the initial
comparison: Logistic Regression reached its training limit without converging, and a separate
check allowing more iterations produced 83.3% accuracy. My contribution emphasized comparing
models fairly, interpreting their results clearly, and checking training settings before choosing a
final model.

---

## Member 4 - [Name]
### Contribution Area: Feature Selection and Experimentation

[Member 4: Write your contribution here.]

---

## Member 5 - Hashim Sayed Hoosini
### Contribution Area: Machine Learning Types and Real-World Applications

My contribution to Group 4 focuses on Parts 7, 8, and 9 of the lab, which cover learning types and real-world applications.
In Part 7 (Hands-On Practice: Build Your Own Model), I ran the code using different features—such as alcohol, color intensity, and proline—and watched the model accuracy change from 0.889 to 0.833. This highlighted how drastically different features can alter model performance.
For the Part 8 Assessment (Understanding ML Concepts), we can use supervised learning to predict house prices. For Scenario 2, grouping customers by purchasing behavior without knowing the groups beforehand, we use unsupervised learning. To teach a robot to play chess by having it play many games, we use reinforcement learning. Classifying emails as spam or not spam using labeled data is another example of supervised learning. Finally, finding hidden topics in news articles without predefined categories relies on unsupervised learning.
Regarding real-world applications, recommendation systems (like Netflix and Amazon) utilize hybrid machine learning recommendation systems. Banks and credit card companies use a mix of supervised learning, unsupervised learning, and deep learning models. Specifically, they use classification for supervised learning and anomaly detection for unsupervised learning.

