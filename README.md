# task-7-SVM
This task involved building and evaluating a binary classification model using Support Vector Machines (SVM) on the Breast Cancer dataset.

Steps Performed:

##1. Data Loading and Preparation:

Loaded the breast cancer dataset from a CSV file.

Dropped the irrelevant id column.

Encoded the target column diagnosis ('M' as 1, 'B' as 0).

Split the dataset into training and testing sets.

##2. SVM Model Training:

Trained an SVM classifier using both linear and RBF kernels.

Predicted outcomes on the test set.

Evaluated model performance using accuracy, confusion matrix, and classification report.

##3. Visualization:

Selected two features (radius_mean and texture_mean) to create a 2D dataset.

Plotted decision boundaries for both linear and RBF kernels to visualize classification.

##4. Hyperparameter Tuning:

Used GridSearchCV to find the best combination of C and gamma for the RBF kernel.

Applied 5-fold cross-validation to evaluate different parameter sets.

##5. Cross-Validation:

Used cross_val_score with 5-fold CV to assess model performance.

Reported individual fold scores and average accuracy.

This end-to-end workflow helped in understanding the impact of kernel choices, scaling, and hyperparameter tuning on SVM performance.
