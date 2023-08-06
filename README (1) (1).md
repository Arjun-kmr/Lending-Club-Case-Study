# Lending Club Case Study

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Project Information

> Lending Club is a lending platform that lends money to people in need at an interest rate based on their credit history and other factors. In this blog, we will analyze this data and pre-process it based on our need and build a machine learning model that can identify a potential defaulter based on customer history of transactions with Lending Club..

### Project Background

> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

### Project Statement

> Find the driving factors which lead to the defaulted loans which are major source of loss for the company.

### Data Set

> The data set is a csv file with the loan data for the Lending Club.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Applicants who opted for higher term (60 months) tend to default more than others.
- Applicants who got loan for higher interest rate tend to default more than others.
- Applicants with home ownership as “OTHER” tend to default more likely than rest of the categories. Also, there are no defaulters in category “NONE”
- Surprisingly, Loan Applications whose Income is verified defaults more than others by at least 2%. May be verification process needs to be revisited.
- Applicants whose purpose of loan is “educational” or “small business” tend to default more than other categories by huge difference between 8 % - 17 %.
- Applicants whose employment length is missing also shows similar pattern for 60 months
- Applicants with 60 months term and verification status as “Source Verified” and “Verified” tend to default more than other combinations
- Applicants with no employment length specified tend to default more for educational purpose
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Pandas - version 1.5.3
- NumPy - version 1.23.5
- Seaborn - version 0.12.2
- MatplotLib - version 3.7.1
- Jupiter - 1.0.0
- Git - 2.41.0
- Github

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contributors

Arjun Kumar
Aratrika Chaudhury



<!-- Optional -->

<!-- ## License -->

## License

This project is open source and available without restrictions.

<!-- You don't have to include all sections - just the one's relevant to your project -->
