# Lending Club Case Study
> The project involves a finance company specializing in urban loans. Loan decisions balance potential loss from non-repayment against missed business. Historical applicant data aims to reveal default patterns for informed actions like denial, adjusted loan terms, or higher rates. The study focuses on Exploratory Data Analysis (EDA) to uncover how consumer and loan attributes impact default tendencies.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- 

The company's loan evaluation process leads to two possible outcomes. Upon loan approval, three scenarios emerge:

Borrowers who fully repay both the principal and interest are termed "Fully Paid."
"Current" status is given to those who are actively repaying their installments, indicating a non-default situation.
If borrowers fail to make timely payments for an extended period, they are labeled as "Charged-off," signifying loan default.
Conversely, for rejected loans, no transaction history exists in the dataset due to the absence of approval, resulting in missing data for those applicants. These distinctions guide the company's understanding of repayment patterns and default risk assessment.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

 > The following factors highly determine the loan defaulting outcomes 
 * Interest Rate 
 * Annual Income 
 * DTI
 * Verification Status

> Other Factors affecting the loan outcomes 
* Grade G and F loans are the most risky loans to be given
* Most of the defaults happened in the later months of the year like sep, out, nov, dec
* Credit card and debt consolidation being the major risky sectors for giving out the loan
* We see a High Number of defaults from states like NE,ID,and NV, Where NE being the extremely highest
* Risk increases as the sub grade of loan increases example A1 A2 A3 so on
* Most of the people who default loan have been charged a higher interest rate
* Most of the people who default loan have a slightly lower annual income


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Pandas - version 1.5.3
NumPy - version 1.23.5
Seaborn - version 0.12.2
MatplotLib - version 3.7.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.


## Contact
Created by [@priyanshu966106] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->