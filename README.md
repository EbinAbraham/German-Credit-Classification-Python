German-Credit-Classification-Python

==========================================================================================================================
<h2> German Credit Classification
==========================================================================================================================

<h4> Overview

The dataset given is downloaded from Kaggle. The objective of the project is to classify loan applicants into risk and<br>
non-risk applicant based on their profile

==========================================================================================================================

<h4> Dataset

Number Of Observations: 1000

Age			- Age of the applicant<br>
Sex			- Gender of the applicant<br>
Job			- 0-unskilled and non-resident, 1-unskilled and resident, 2-skilled, 3-highly skilled<br>
Housing			- WHether house is own, rent or free<br>
Saving accounts		- Little, moderate, quite rich or rich<br>
Checking account	- How many time the applicant checks the account<br>	
Credit amount		- Credit amount in account at present<br>
Duration		- Time in months<br>
Purpose			- car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, <br>
			  vacation/others<br>
Risk			- Risk is bad or good<br>

==========================================================================================================================

<h4>Processing

There were some missing values. These missing values were converted to as new categories. The variables age, duaration<br>
and credit amounts were binned based on the log likelihood. The data was found to be unbalanced hence SMOTE was used for<br>
balancing the data.The Random Forest Classifier was used for processing the dataframe.<br>

==========================================================================================================================

<h4>Result

The training accuracy was obtained at 79.85% and Testing accuracy at 80%. The F1 score = 0.8014 and the AUC score was<br>
0.799 to validate the same. 

==========================================================================================================================