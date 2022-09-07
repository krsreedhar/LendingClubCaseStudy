# Project Name
> Lending Club Case Study Project


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project or case study helps in analyzing the loan borrower's data.
- It helps in providing recommendations to the investors to make right decision.
    - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
    - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- Lending Club is an online market-place where 2 types of people come together for business – The borrower who wants to borrow money for various purposes (credit card payment, marriage etc.) and the investor who wants to lend money to earn interest ultimately. 
- As a company, Lending Club wants to identify the risky loan applicants who have higher chances of defaulting so that credit loss to the company is reduced as much as possible. There is a need to identify some consumer and loan attributes to meet this purpose.
- loan.csv - contains the complete loan data for all loans issued through the time period 2007 t0 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- People with 10 or more years of experience are less likely to be defaulted because of higher annual income and can be trusted to give a loan. 
- On the same lines the company should avoid giving loans to people having less then 2 years of experience as they tend to default more. Since raising interest might not help, the company can avoid giving loans to these bracket of people
- People taking loan for 60 or more months have higher chances of being charged off. In this case, the company can raise the interest rate for giving loans for 60 or more months. 
- People having their own homes and taking loans should be highly trusted. However, we do understand from data that such proportion of people are less. The company should be cautious about giving loans to  people on mortgaged homes and interest rate should be higher for these people. 
- Debt consolidation and credit card payment are the 2 areas where people taking loans default the most. The company should be aware before giving loans for these 2 purposes. Charging higher interest rate might be helpful in this area.
- People from FL, NJ, MD have higher rate of defaulters as compared to the combined defaulters of other states. The company needs to be cautious before giving loans to people from these states. Charging higher interest rates from people of these states can be a helpful measure as they constitute a good number of people who take loans. 
- People making higher inquiries to take loans tend to default more against people making less enquiries. This can happen because a person making more enquiries for the loan is still trying to figure out a way to pay back and can try to negotiate for a lower interest rate over calls. Company needs to be cautious about these bracket of people.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - 3.9.2
- Anaconda - Jupyter Notebook 6.4.8
- Libraries used - numpy, pandas, matplotlib.pyplot, seaborn, plotly

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- References - stackoverflow.com, upgrad live sessions
    - https://www.geeksforgeeks.org/how-to-print-an-entire-pandas-dataframe-in-python/
    - https://cmdlinetips.com/2019/02/how-to-make-histogram-in-python-with-pandas-and-seaborn/
    - https://thispointer.com/drop-rows-with-all-zeros-in-a-pandas-dataframe/



## Contact
Created by [@krsreedhar, @chandeeparora19] - feel free to contact me!


