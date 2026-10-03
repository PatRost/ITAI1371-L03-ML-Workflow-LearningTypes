# ITAI 1371 - Module 3 Group Reflection Journal

## Group 4

This document contains the individual reflections of each group member for the Module 3 Machine Learning Workflow and Types of Learning lab.

---

## Member 1 - Patrick Rostand Gandjouon Tchassem

### Reflection

This module helped me understand machine learning better because I was able to see how the different types of machine learning work and practice the complete workflow.

One of the main things I learned was the difference between supervised, unsupervised, and reinforcement learning. I think supervised learning interests me the most because it is easier for me to understand when I can see the input data and the correct answers.

The Wine classification project also helped me understand the machine learning workflow. I learned that we need to explore and prepare the data before training a model. We also need to split the data into training and testing sets so we can evaluate the model on data it has not seen before.

One of the most interesting parts for me was feature selection. The original Logistic Regression model had 88.9% accuracy. After experimenting with flavanoids, color_intensity, and proline, the accuracy increased to 91.7%. This showed me that choosing the right features can affect how well a model performs.

The most challenging part for me was understanding all the different steps in the machine learning workflow. I learned that machine learning is not only about training a model. It includes understanding the problem, preparing the data, training and testing models, evaluating the results, and improving the model.

Overall, this lab gave me a better understanding of how a machine learning project works from beginning to end. I would like to learn more about feature selection, overfitting, and how to improve model performance.

---

## Member 2 - [Saimi Manasiya]

### Reflection

Reflection – Data Preparation & Splitting

Working on the Data Preparation and Splitting section of this lab helped me understand that preparing data is an important part of the machine learning process. Before this lab, I understood the general idea of training a machine learning model, but I had a better understanding of how the dataset needs to be organized before a model can actually learn from it.

One of the main things I learned was the difference between the features (X) and the target variable (y). The features provide the information that the model uses to make predictions, while the target is what the model is trying to predict. Understanding this separation helped me see how a machine learning problem is translated into data that a model can work with.

I also learned how an 80/20 train-test split works and why it is necessary. The training data allows the model to learn patterns, while the testing data provides unseen examples for evaluating how the model performs. This helped me understand why we should not simply train and test a model using the same data.

The most challenging part for me was making sure that the features and target were selected correctly and understanding how the data was divided without affecting the relationship between the inputs and their corresponding labels. Working through the process in Google Colab made it easier for me to understand each step and see how the prepared data was used later in the workflow.

Overall, this lab gave me a clearer understanding of the early stages of a machine learning workflow. I learned that good data preparation is essential because the model depends on properly organized data. I also became more comfortable working with a dataset in Google Colab and understanding how data preparation connects to the model training and evaluation stages completed by the rest of my team.

## Member 3 - [Kenneth Kouokam]

### Reflection

My main takeaway from this lab is that evaluating a model requires more than looking for the highest
accuracy. My assigned area was Model Training and Evaluation, which connects the earlier work of
preparing data with the final task of explaining what the predictions mean. In Lab 02, the focus was on
tables, calculations, and charts. Here, those tools support a larger question: how well can a model use
measurements to classify examples it has not seen during training?

The Wine project helps me distinguish the learning types. It is supervised learning because the chemical
measurements come with known wine-class labels. Even though one model is called Logistic Regression,
its job here is classification. Unsupervised learning would look for groups without those labels, while
reinforcement learning would involve decisions and feedback from an environment. I see these
differences as differences in the information available to learn from, rather than simply different algorithm
names.

The initial model comparison shows why results need context. With the starter's four features and fixed
split, Logistic Regression correctly classified 32 of 36 test samples, giving 88.9% accuracy. The Decision
Tree correctly classified 30, giving 83.3%. The difference is only two predictions, so I would not treat it as
proof that Logistic Regression is always better. Both models need the same test examples for a useful
comparison, and a small test set limits how confidently I can generalize the result.

The classification report and confusion matrix make the result more meaningful. In the initial Logistic
Regression output, all 12 class_0 examples were correct, but only 7 of 10 class_2 examples were
identified correctly. The remaining three were predicted as class_1. This shows how a fairly high overall
accuracy can hide weaker performance on one class. Precision asks how reliable a predicted class is,
while recall asks how many actual examples of that class were found. I would choose which errors matter
most based on the problem being solved.

A useful lesson from checking the training settings is that a displayed result is not automatically a settled
result. The starter's Logistic Regression reached its 100-iteration limit without converging. A separate
check allowing more iterations converged and produced 83.3% accuracy. I take this as a reason to pay
attention to warnings and report settings clearly. Finishing the optimization does not guarantee a higher
score on every test set, and the initial ranking should not be treated as a final conclusion.

For future work, I would consider feature scaling and compare settings through cross-validation using the
training data. I would keep a separate final test set for the last evaluation, since repeatedly using it to
choose models can make performance appear better than it really is. The workflow matters because each
decision affects the next stage. My goal is to explain both what a model achieved and what the evidence
is too limited to establish.

---

## Member 4 - [Name]

### Reflection

[Member 4: Write your individual reflection here.]

---

## Member 5 - Hashim Sayed Hoosini

### Reflection
This assignment helped me understand the different types of machine learning, which are supervised learning, unsupervised learning, and reinforcement learning. For this project, we used supervised learning.

I learned that in supervised learning, the model learns from examples, which are the wine measurements plus the correct wine class. I also learned that classification is a technique where the model learns from a labeled dataset to predict the category or class of new, unseen data. Moreover, I learned that data collection, data preparation and exploration, and splitting the data before model training are necessary steps in machine learning.

From the previous project, I learned about EDA (Exploratory Data Analysis). I ran each code cell and studied each feature, which helped me learn about the 178 samples, 13 features, and three classes. I also learned that X represents the wine features and y represents the wine class. The data was distributed relatively evenly among the classes, so I understood that the data was not imbalanced. For data quality, there were zero missing values, and I studied the correlations between the data.

In addition, this lab helped me learn that choosing the right model for a dataset is important. Logistic Regression and Decision Tree were used for model training and to evaluate model performance. Logistic Regression resulted in 88.9% accuracy, and Decision Tree resulted in 83.3% accuracy. Then I ran the model with different features, such as alcohol, color intensity, and proline, and the model accuracy changed from 0.889 to 0.833. I noticed how different features can change model performance.

For me, the challenging part of this lab was understanding why we need to split the data, train the model on 80% of the data, and test the model on 20% of the data. With this lab, I learned that we split the data into an 80% training set and a 20% testing set to teach the machine learning model real-world patterns while keeping fresh data hidden to measure the accuracy of the model on unseen data.

Overall, this lab helped me learn the machine learning workflow, from data collection to model performance.
