# Agaricus-Lepiota Dataset Classification using Support Vector Machines (SVM)

This project aims to classify the Agaricus-Lepiota mushroom dataset using Support Vector Machines (SVM). SVM is a powerful machine learning algorithm used for classification, regression, and outlier detection. In this project, I used the Nu-Support Vector Classification (NuSVC) algorithm to classify the mushrooms as edible or poisonous.

## Dataset

The Agaricus-Lepiota dataset contains information about various features of mushrooms, such as cap color, odor, stalk shape, etc. The dataset has 8124 instances with 23 attributes, and each instance is labeled as either edible (e) or poisonous (p).

## Libraries Used

Used the following libraries for this project:

•NumPy

•Pandas

•scikit-learn

•Matplotlib

## Workflow
•Load the dataset using Pandas.

•Convert categorical features to binary features using one-hot encoding.

•Separate features and target variable.

•Divide the dataset into 70-30 for training and testing with 10 different samples.

•Create the NuSVC model object.

•Train the model on the training set.

•Predict the target values for the test set using the trained model.

•Evaluate the performance of the model using accuracy score.

•Find the sample with maximum accuracy.

•Create a NuSVC model object with the best parameters.

•Train the model on the training set with best parameters.

•Plot the convergence graph for the sample whose accuracy is maximum.

•Plot the graph of accuracy vs number of iterations.

## Results

Model achieved an accuracy of 0.906 on the test set. The best parameters were kernel='rbf', nu=0.5, max_iter=1000, tol=0.001.