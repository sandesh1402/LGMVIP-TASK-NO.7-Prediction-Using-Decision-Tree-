# LGMVIP-TASK-NO.7-Prediction-Using-Decision-Tree-
In this project, we aim to create a Decision Tree classifier and visualize it graphically. The purpose is to train the classifier on a given dataset, in this case, the Iris dataset, and then use it to predict the class of new data based on the learned patterns from the training set.
Here's a brief explanation of the steps involved in this project:

Importing Libraries: We begin by importing the necessary libraries. In this case, we import sklearn.datasets to load the Iris dataset, sklearn.tree for the Decision Tree classifier, and matplotlib.pyplot for visualization.

Loading the Dataset: We load the Iris dataset using the load_iris() function from sklearn.datasets. The dataset contains samples of iris flowers with their corresponding features and classes.

Creating the Decision Tree Classifier: We create an instance of the DecisionTreeClassifier class from sklearn.tree. This classifier uses the Decision Tree algorithm to learn patterns in the training data and make predictions.

Training the Classifier: We fit the classifier to the training data, which consists of the feature vectors X and the corresponding target classes y. The classifier learns the patterns in the data and builds a Decision Tree model.

Visualizing the Decision Tree: We use matplotlib.pyplot to visualize the Decision Tree. The tree.plot_tree() function generates a graphical representation of the Decision Tree based on the learned patterns. We provide the feature names and class names to make the visualization more interpretable.

Predicting on New Data: We demonstrate how to use the trained classifier to make predictions on new, unseen data. We create a new data array new_data with three samples, each having four feature values. We then use the trained classifier's predict() method to predict the class for each sample.

Displaying the Predictions: We print the predicted classes for the new data samples. These predictions are based on the learned patterns in the training data and the decision rules of the Decision Tree.
