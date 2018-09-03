German-Credit-Classification-Python

==========================================================================================================================
>>>> German Credit Classification
==========================================================================================================================

>>> Overview

The dataset given is downloaded from Kaggle. The objective of the project is to classify loan applicants into risk and
non-risk applicant based on their profile

==========================================================================================================================

>>> Dataset

Number Of Observations: 1000

Age			- Age of the applicant
Sex			- Gender of the applicant
Job			- 0-unskilled and non-resident, 1-unskilled and resident, 2-skilled, 3-highly skilled
Housing			- WHether house is own, rent or free
Saving accounts		- Little, moderate, quite rich or rich
Checking account	- How many time the applicant checks the account	
Credit amount		- Credit amount in account at present
Duration		- Time in months
Purpose			- car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, 
			  vacation/others
Risk			- Risk is bad or good

==========================================================================================================================

>>>Processing

There were some missing values. These missing values were converted to as new categories. The variables age, duaration
and credit amounts were binned based on the log likelihood. The data was found to be unbalanced hence SMOTE was used for
balancing the data.The Random Forest Classifier was used for processing the dataframe.

==========================================================================================================================

>>>Result

The training accuracy was obtained at 79.85% and Testing accuracy at 80%. The F1 score = 0.8014 and the AUC score was
0.799 to validate the same. 

==========================================================================================================================