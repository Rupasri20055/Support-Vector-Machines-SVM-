# Support-Vector-Machines-SVM-
Task 7: Support Vector Machines (SVM)

About this Task:
In this task, I worked with the famous Iris dataset (filtered for two classes to make it a binary classification problem) to implement and understand how Support Vector Machines (SVM) work for both linear and non-linear (RBF kernel) classification.

 What I Did:
 
1️ Loaded the Iris dataset from a CSV file and converted categorical labels to numeric using LabelEncoder().

2️ Filtered the dataset to keep only two classes: Iris-setosa and Iris-versicolor for a binary classification problem.

3️ Selected two numeric features: PetalLengthCm and PetalWidthCm for easy 2D decision boundary visualization.

4️ Split the data into training and testing sets using train_test_split().

5️ Standardized the features using StandardScaler to bring them to the same scale, which is important for SVM.

6️ Trained an SVM classifier with a Linear Kernel using sklearn.svm.SVC(kernel='linear').

7️ Visualized the decision boundary for the linear model using contour plots.

8️ Trained another SVM with an RBF Kernel (kernel='rbf') and visualized its decision boundary.

9️ Tuned hyperparameters like C and gamma by testing different values and observing their effects on accuracy.

10 Applied Cross-Validation (5-Fold) using cross_val_score() to evaluate model performance more reliably.
