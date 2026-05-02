Lab 9: Decision Trees and Random Forests
Overview
The goal of this lab is to use LendingClub.com data to predict loan repayment. We implemented two different machine learning models to classify whether a borrower paid their loan in full.

Steps Completed
Data Exploration: Visualized FICO scores and interest rates using histograms and jointplots.

Data Transformation: Handled the categorical 'purpose' column by creating dummy variables.

Train-Test Split: Divided the dataset into training and testing sets (70/30 split).

Model Training: Trained a Single Decision Tree and a Random Forest Classifier with 600 estimators.

Results
Decision Tree: Achieved an accuracy of 74%. It showed a higher recall for the 'not fully paid' class (0.20).

Random Forest: Achieved a higher overall accuracy of 85%, but had a very low recall for the 'not fully paid' class (0.01).

Final Conclusion
The Random Forest model is more accurate overall. However, the Decision Tree is better at catching the high-risk borrowers who do not pay back their loans, as indicated by the higher recall for Class 1.
