# Bank Marketing Classification Model

##  Project Overview
This project analyzes a bank marketing dataset to predict whether a customer will subscribe to a term deposit. The goal is to improve marketing efficiency by identifying high-probability customers before outreach.

##  Business Problem
Banks often run large-scale marketing campaigns with low conversion rates. Contacting every customer is costly and inefficient. This project explores how predictive modeling can be used to:
- Identify likely subscribers
- Reduce unnecessary outreach
- Improve campaign ROI

##  Models Used
- Decision Tree
- K-Nearest Neighbors (K-NN)

##  Key Insight
Although K-NN achieved ~88% accuracy, it predicted the majority class ("No") for all observations due to class imbalance.

This demonstrates that:
> Accuracy alone is not a reliable metric for imbalanced datasets.

The Decision Tree model provided better practical value by correctly identifying actual subscribers.

##  Evaluation Methods
- Confusion Matrix
- Accuracy vs True Positive Detection
- Class distribution analysis
![Workflow](Bank Classificaton Project.png)

##  Business Impact
- Enables targeted marketing campaigns
- Reduces wasted outreach efforts
- Improves customer conversion rates
- Supports data-driven decision-making

##  Tools Used
- RapidMiner
- Python (conceptual understanding)
- Classification modeling techniques

##  Files Included
- `Bank Marketing Classification Cade Miller.rmp` → RapidMiner process
- `project-report.pdf` → Full project write-up

##  Future Improvements
- Apply resampling techniques (SMOTE, undersampling)
- Test additional models (Logistic Regression, Random Forest)
- Deploy as a scoring tool for real-time predictions

##  Author
Cade Miller  
Business Analytics Student | Aspiring BI Analyst
