# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

Company:Codtech It solutions

Name:Mithun M

Intern Id:CT04DG1410

Domain:Data Analytics

Duration:4weeks

Mentor:Neela Santosh




# 🧪 Feature Selection and Model Evaluation

This project demonstrates the practical use of feature selection, machine learning model training, and performance evaluation using the Breast Cancer Wisconsin dataset from scikit-learn. The aim is to identify the most significant features in predicting whether a tumor is malignant or benign and build an efficient classification model using only those features.

We begin by loading the dataset, which contains 30 numerical features extracted from digitized images of fine needle aspirate (FNA) of breast masses. To reduce dimensionality and improve model performance, we apply **SelectKBest** feature selection using the ANOVA F-value as a statistical test. This method helps us identify the top 10 most relevant features that contribute to the classification task.

Next, we split the dataset into training and testing subsets and train a **RandomForestClassifier**, a robust ensemble learning method known for handling high-dimensional data well and providing feature importance scores. After training the model on the selected features, we evaluate its performance using various metrics including **accuracy score**, **classification report**, and a **confusion matrix**. These metrics help us assess the model’s ability to correctly predict malignant and benign tumors.

Finally, we visualize the importance of each selected feature using a bar chart, offering insights into which features had the most influence on the model's decisions. This visualization not only aids interpretability but also helps in validating the feature selection step.





output


![Image](https://github.com/user-attachments/assets/83b91d27-4844-4738-8ad7-149ff769bb63)



