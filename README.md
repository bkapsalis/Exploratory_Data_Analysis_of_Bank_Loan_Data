# Exporatory-Data-Analysis

To view html download and save as html and open in brouser.

# Sample Results:
Exploratory Data Analysis can find a great amount of information from a data set alone with no additional information. From the data we learn:
- When Someone Said 'Stop Making All Loans!'
- Maximum Loan Amount
- Minimum Credit Score To Get a Loan
- Profit and Loss by Credit Score
- Profit and Loss by Loan Ordination
- Possible Fraudulent or Incompetent Loans

## NetProfit vs LoanOriginationMonth
![Alt text](/imgs/img2.png?raw=true "Optional Title")

This graph demonstrates that essentially all loans stopped for some reason late 2008 for about 9 months. In the next few graphs we will see some possible reasons why this happened.

The above graph uses an alpha of 1/40 was used to better visualize the distribution. This means that 40 loans at the same  point on the graph would result in a black dot. 20 loans at one point would be a gray. If one dot represented one loan it would be a very light gray.



![Alt text](/imgs/img6.png?raw=true "Optional Title")

The graph above shows the distributions of loans with the original loan amount vs. the credit score of the borrower. This was done for loans granted before January 2009(pre2009) and after January 2009(post2009). In late 2008 there was a market crash and it appears loans were granted differently before and after January 2009. This graph was created to see if we can determine what the criteria for granting a loan were before January 2009 and if the criteria changed after January 2009.

The blue line represents the median loan amount over the different credit scores of the borrowers. An alpha of 1/40 was used to better visualize the distribution. The dotted blue lines below and above the median line represent the 10th and 90th Quintile, respectively. The dotted red line represents the sum of all loans across the credit scores of the borrowers.

From these graphs we can clearly see some of the loan criteria. For example prior to January 2009 the maximum loan was $25,000 and after January 2009 the maximum loan was $35,000. Below are other apparent criteria for granting loans before and after January 2009:

Apparent pre2009 guidelines for loan approval:
- no loans above $25,000
- no loans above $15,000 with a credit score less than 550
- no loans above about $2,000 with a credit score less than 440
- no loans with a credit score less than about 380
Apparent post2009 guidelines for loan approval:
- no loans above $35,000
- no loans above $25,000 with a credit score less than 710
- no loans above $15,000 with a credit score less than 650
- no loans with a credit score less than about 600
This may explain the increase in NetProfit after 2009 we will see below.







![Alt text](/imgs/img3.png?raw=true "Optional Title")

![Alt text](/imgs/img4.png?raw=true "Optional Title")
![Alt text](/imgs/img1.png?raw=true "Optional Title")













#https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0
