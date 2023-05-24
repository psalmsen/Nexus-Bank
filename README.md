# Nexus-Bank
Analysis of the bank's customer demography. 

I was reached out to by a bank which has been having issues with customers not making deposits. Several campaign has been done to sensitize there customers, but thers has been a very little improvement to the the deposits made by the customers.

Receiving the dataset from the banks's database, I created a null Hypothesis to help me better understand the problem. The hypothesis I created are;
  - Customers that do not make deposit will not be granted loans.
  - High paying jobs will likely have access to loans compared to the other job types.
  - Entrepreneurs should make more deposit because they will need to more savings.
  - Collaterals should be requested from customers seeking loans.

After alighting the hypothesis, I looked dived in to the dataset and checked for irregularities such as missing data and ouliers. I critically analyzed the outliers i found to see hiw logical they are nd removed the ones that are not logical, retaining the logical ones.

I worked with the cleaned data and a carried out various analysis to see the trend the customers operate, the demography of the customers how often they requested for loans and also how sucessful the campaign is.

From my analysis, I found out the following:
  -  I is observed that the previous campaign appears to be more sucessful as most of the customers made deposit to the bank and on the average, it only takes 1.3 contact to convince a customer to make deposit unlike the new campaign that on the average, a contact of 2.0 must be made to make deposit by a customer.

- I also observed that the bank awards housing loans to 52.5% of customers and 15.4% of personal loans to customers that do not make deposit to the bank over a period of time.

- Over 90% of customers across all the job types that are defaulters, are customers that did not make deposit to the bank. 

- The chart also reveals that there is a high probability of customers to make deposit when contacted for a duration of 290s to 520s.

- The analysis revealed that only 9.6% of the entire customers made deposit.

- Customers reached out to through cellular and telephone in the previous campaign have a higher probability of customers to make deposits.
- The entrepreneur job type recorded the highest percentage of those that defaulted (recording 3.7% of the 100% that are entrepreneurs), while students are the least that defaulted of the 100% that are students.

With the analysis, it is probably obvious that the bank is retaining her customers by giving out loans to them, but more data will be needed to back uo this claim, hence, more data will be rquired such as;
- The last day deposit was made by the customer.
- Amount of loan given
- Requirements for approving loan.
- The type of account operated by the customer.
- Collateral for loan approval.
- Number of times each customer have been granted loan and defaulted.

To assist the bank in preventing giving out loans to customers that will not make deposits, I carried out a machine learning algorithm. I used differnt models to checck the most suitable of the model after normalizing the dataset to prevent overfitting and underfitting. In
In my analyzis, I figured that it will be costly for the bank to give out loans to customers that will not make deposit, hence, it is necessary to ensure that the machine learning model fits well to predict with a high probability customers that will not make deposit.

Going with the XGB Classifer which gives a better analytical precision as shown below:
- Score of train: 0.8986367188630641
- Score of test: 0.9063440611252604
- Logistic Regression
- Accuracy: 0.9260245427182218
- Precision: 0.6374045801526718
- Recall: 0.42656449553001274
- F1-score: 0.5110941086457537
- AUC-ROC: 0.7011880402538669
- R_squared score:  0.10255858703366338
With this, and getting more data as listed above to train the model, the model can help with a high prediction to predict customers behaviour towards making deposit or not.


