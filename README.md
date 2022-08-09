# Lending_Club_Upgrad_VibhorMalik_ManojBisht
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
> Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
> If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
> In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 


## Table of Contents
- [Lending_Club_Upgrad_VibhorMalik_ManojBisht](#lending_club_upgrad_vibhormalik_manojbisht)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Conclusions](#conclusions)
  - [Technologies Used](#technologies-used)
  - [Acknowledgements and References](#acknowledgements-and-references)
  - [Created By](#created-by)

## General Information
- A *consumer finance company* which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. *Two types of risks* are associated with the bank’s decision:
- If the applicant is *likely to repay the loan*, then not approving the loan results in a *loss of business* to the company
- If the applicant is *not likely to repay the loan*, i.e. he/she is likely to default, then approving the loan may lead to a *financial loss* for the company

- The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- In this case study, you will use EDA to understand how *consumer attributes* and *loan attributes* influence the tendency of default.


## Conclusions
- As we have noticed that maximum defaults are from loans which are provided int the month of `May`, `Sep`, `Oct`, `Dec`, thus Bank has to be careful with loan application, in these months
- `small_business` has highest percentage of default and `debt consolidation` has maximun number of defaults, So these two need to be check carefully
-  As we have noticed that maximum defaults are from loans where there was either high loan granted or loan with very high interest rates thus High `loan amount` and High `interest Rate` should be avoided to be given to avoid defaulters
- Bank Need to more carefull for State `NE` as most defauters are from this state
- for loans with  purpose of `small business` and `debt consolidation` avoid giving loans to `E`, `F` & `G` Grade and give term max 36 months as 60 month term have most defaults in the past
- Bank has to be more careful while granting loans to low salary peoples ranging from `4k to 17.2k` as most defaults has been seen form these categories


## Technologies Used
- [Python - Version 3.9.7](https://www.python.org/download/releases/3.0/)
- [numpy - Version 1.20.3](https://github.com/numpy)
- [pandas - Version 1.3.4](https://github.com/pandas-dev/pandas)
- [matplotlib - Version 3.5.1](https://github.com/matplotlib)
- [seaborn - Version 0.11.2](https://github.com/seaborn)
- [Jupyter Notebook - Version 6.4.5]()
- [Anaconda - Version 2.2.0]()


## Acknowledgements and References 
- The project reference course details from upGrads .
- Live presentation and Guide about the brief of the project [Siddhesh Gunjal]()
- PI session and Live presention about the brief of the project [Rohit Gupta]() 
- [Loading a csv file from GitHub in Python](https://medium.com/towards-entrepreneurship/importing-a-csv-file-from-github-in-a-jupyter-notebook-e2c28e7e74a5)

## Created By 
- [Vibhor Malik]()
- [Manoj Bisht](https://www.linkedin.com/in/manoj-bisht-b293a657/)



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->