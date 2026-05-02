Loan Repayment Prediction
This repository contains a Machine Learning project to predict whether a borrower will pay back their loan in full using data from LendingClub.com. The project compares the performance of a Single Decision Tree versus a Random Forest Classifier.

Project Highlights
Task: Binary Classification (Paid in full vs. Not paid).

Dataset: LendingClub loan data (2007-2010).

Models Used: Decision Tree, Random Forest (600 estimators).

Preprocessing: Handled categorical data using Dummy Variables.

Exploratory Data Analysis (EDA)
During the analysis, several visualizations were created to understand the data:

FICO Scores: Histograms showed that borrowers with higher FICO scores are more likely to meet credit policies.

Interest Rates: A clear trend showed that interest rates decrease as FICO scores increase.

Purpose: Most loans were for "debt consolidation".

Model Comparison & Results
The models were evaluated using a classification_report and a confusion_matrix. Below is a summary of the performance on the test set (30% of the data):

Metric	Decision Tree	Random Forest
Overall Accuracy	74%	85%
Recall (Class 1)	0.20	0.01
F1-Score (Class 1)	0.18	0.02

💡 Key Conclusion
While the Random Forest achieved a higher Overall Accuracy (85%), it struggled to identify borrowers who would not pay back (Class 1). The Decision Tree, although less accurate overall, was more effective at detecting high-risk borrowers with a significantly higher Recall.
