
German-Credit-Classification-Python

==================================================================================
<h2> German Credit Classification</h2>
==================================================================================
<h4> Overview </h4>

<p>The dataset given is downloaded from Kaggle. The objective of the project is to classify loan applicants into risk and<br>
non-risk applicant based on their profile</p>

==================================================================================

<h4> Dataset</h4>

Number Of Observations: 1000

<pre class="tab">Age			- Age of the applicant</pre><br>
<pre class="tab">Sex			- Gender of the applicant</pre><br>
<pre class="tab">Job			- 0-unskilled and non-resident, 1-unskilled and resident, 2-skilled, 3-highly skilled</pre><br>
<pre class="tab">Housing			- WHether house is own, rent or free</pre><br>
<pre class="tab">Saving accounts		- Little, moderate, quite rich or rich</pre><br>
<pre class="tab">Checking account	- How many time the applicant checks the account</pre><br>	
<pre class="tab">Credit amount		- Credit amount in account at present</pre><br>
<pre class="tab">Duration		- Time in months</pre><br>
<pre class="tab">Purpose			- car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, 
                                                  vacation/others</pre> <br>
<pre class="tab">Risk			- Risk is bad or good</pre><br>

==================================================================================

<h4>Processing</h4>

<p>There were some missing values. These missing values were converted to as new categories. The variables age, duaration and<br>
credit amounts were binned based on the log likelihood. The data was found to be unbalanced hence SMOTE was used for<br>
balancing the data.The Random Forest Classifier was used for processing the dataframe.<br></p>

==================================================================================

<h4>Result</h4>

<p>The training accuracy was obtained at 79.85% and Testing accuracy at 80%. The F1 score = 0.8014 and the AUC score was<br>
0.799 to validate the same. </p>

==================================================================================