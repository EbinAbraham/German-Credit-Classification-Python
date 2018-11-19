
German-Credit-Classification-Python

==================================================================================
<h2> German Credit Classification</h2>
==================================================================================
<h4> Overview </h4>

<p ALIGN=JUSTIFY>The dataset given is downloaded from Kaggle. The objective of the project is to classify loan applicants into risk and
non-risk applicant based on their profile</p>
==================================================================================

<h4> Dataset</h4>

Number Of Observations: 1000



| Feature          | Description                                                  |
| ---------------- | ------------------------------------------------------------ |
| Age              | Age of the applicant                                         |
| Sex              | Gender of the applicant                                      |
| Job              | 0-unskilled and non-resident, 1-unskilled and resident, 2-skilled, 3-highly skilled |
| Housing          | Whether house is own, rent or free                           |
| Savings accounts | Little, moderate, quite rich or rich                         |
| Checking account | How much the applicant checks the account                    |
| Credit amount    | Credit amount in account at present                          |
| Duration         | Time in months                                               |
| Purpose          | Car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, vacation/others |
| Risk             | Risk is bad or good                                          |



==================================================================================

<h4>Processing</h4>

<p ALIGN=JUSTIFY>There were some missing values. These missing values were converted to as new categories 'nval'. The variables age, duaration and credit amounts were binned based on the log likelihood. The categorical variables was encoded into columns. The variable having less correlation with the output was removed. The data was found to be unbalanced hence SMOTE was used for balancing the data.Three models were build which were Random Forest, Support Vector Classifier and GradientBoosting Classifier.</p>

==================================================================================

<h4>Result</h4>

<p ALIGN=JUSTIFY>Out of the three model Random Forest Classifier gave the best result. The result of the model is as follows:</p>

```
Confusion Matrix:
 [[114  25]
 [ 26 115]]
```

| Metric            | Value   |
| ----------------- | ------- |
| Training Accuracy | 78.12%  |
| Testing Accuracy  | 81.78%  |
| Sensitivity       | 0.81428 |
| Specificity       | 0.82142 |
| F1 Score          | 0.81850 |
| AUC Score         | 0.81787 |



==================================================================================