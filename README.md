# Project Name
> EDA Analysis For Leading Club Case Study.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project involve EDA analysis for the loan provided by the financial institutions/bank .It analysed the historical data for the customers and help the financial institutions/bank to identify the driving factors behind loan default. This project contain deatiled analysis on historical data for Leading Club and provide recommendations which will help the organization to take decision related to defaulters.
- Data set used for Leading club and source data was provided in excel.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Verification status : Charged off count is comparable across category Verified and Source verified (Refer slide 13). Which suggest that improvement is required for verification process as defaulters are reported despite verification.

- Months since last delinq : The number of months since the borrower's last delinquency (Refer slide 12) is nearest for grades ( E, F and G ). Hence are more delinquent. Hence application belonging to such categories should be assessed carefully before approving as they are at higher risk of becoming defaulters. Greater Funded amounts should not be approved for them.

- Purpose :  Purpose of the loan should be assessed carefully as mostly applicants fall into the category of debt consolidation ( Refer slide 15 )

- Employee length : Though our dataset ( univariate analysis for employment length ) indicates that applicants with 10+ years experience are more in number compared to any employment length. Due to large data set around 10+ years , we observe that count of defaulters is high in this category. But why at all are they defaulting? Higher experienced applicants  are opting for more funded amount and the term to repay is 36 months which is lesser compared to other terms. Purpose for opting for loan is Debt consolidation Hence chances for them to   default is higher ( Refer slide 16,17 ). Chances are that more experienced applicants are greater liabilities.

- Term : As mentioned above, large funded amounts and shorter terms ( with existing debts ) might result in an applicant defaulting. ( Refer slide 16,17 )

- Interest Rate: As our analysis shows that for the customer type Garde “G” we are approving loan with high rate of interest but these customers are more prone to default. So approving loan for higher rate of interest will not help.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- We have used python coding to analyze the data and below are the few important libraries name from python which is used in the analysis
- library 1 - pandas
- library 2- numpy
- library 3- seaborn
- library 4- matplotlib
- library 5- warnings
- library 5- warnings

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project is completed after successfully completing the learning session provided by IIITB & UpGrad for the EDA analysis,Pyhton and their libraries like Pandas, numpy ,matplotlib etc.



## Contact
Created by [@githubusername] - @PrakashShri and @poojamaini


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
