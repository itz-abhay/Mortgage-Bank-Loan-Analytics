# Mortgage Bank Loan Analytics

Banks can now use mortgage loan analytics using Data Science techniques. The system can provide detail information of the mortgage loans and the mortgage loan markets. It is a powerful tool for mortgage brokers to seek counterparties and generate trading interests and is useful for the CFOs to conduct what-ifs scenarios on the balance sheets.

Fill in the follow fields in Loan file template:

* Loan ID: to identify the special loan
* Loan Type: to indicate the loan if fixed rate, or balloon loan , or ARM, or AMP (alternative mortgage product).
* Balance:
* Loan program type: to indicate conforming loan, FHA/VA loan, Jumbo loan or sub-prime loan
* Current coupon rate:
* Amortization type: the original amortization term
* Maturity: the maturity loan (the remaining term of the loan)
* FICO Score: the updated fico score
* LTV: the current loan to value ratio
* Loan Size: the loan amount of the loan
* Loan origination location (City & Zip)
* Unit Types (Types of property)
  
The Random Forest model gave the best result on each of the four evaluation criteria used to evaluate the models.The Random Forest model outperforms the all other models when analyzing mortgage applications per day then Decision Tree model. The SVR model scored the worse, SVM on a second place. The percent error of the Random Forest model is around of the actual amount of mortgage applications per day.

## Models Used:

* Linear Regression
* Logistic Regression
* Random Forests (RF)
* Support Vector Regression (SVR)
* Support Vector Machine (SVM)
* k-Nearest Neighbors
* Decision Tree Classifier
