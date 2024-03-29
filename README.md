# Project Name
> Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

### Project Information

> The project is a data science project that uses the lending club data set to predict whether a loan will be defaulted or not.

### Project Background

> This company is the largest **online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures**. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to **‘risky’** applicants is the largest source of financial loss (called credit loss). **Credit loss** is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

### Project Statement

> The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

### Data Set

> The data set is a csv file with the loan data for the Lending Club.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Results from Univariate Analysis:
  
  1. Majority of the Loan Amount Requested/Sanctioned falls between 2500 - 10000 range.
  2. 85.4% of the loans approved was Fully Paid and a 14.6% of loans was defaulted.
  3. Around 22% of the total loan are taken by people who had 10+ Years of employee length, indicating that people tend to take loans more on a later stage of life.
  4. The loan issued increases drastically year by year, 2011 has over 50% of the all issued loans. This can be due to several reasons.
      Life Getting Tougher Over Years
      Recession in 2011
      LC became popular over years
  5. Loan Status vs Interest Rate Box plot gives a strong indication that most of the defaulters tend to fall on higher interest rates when compared to non defaulters
  6. The Percentage of Defaulters Under Each Category WRT Grade barplot gives a clear conclusion/insights that higher the grade at which the loans are taken, more the chance of defaulting.
  7. Around 36% of the loan takers under G category has defulated
  8. Loan Status vs Funded To Income Ratio Box plot gives a slight indication that most of the defaulters fall on high f_to_i ratio value, whereas majority of the Fully Paid are on the lower 
     ratio end
  9. Grade/Sub Grade is linked to Interest rate, Higher the grade higher the interest rate
 10. Term Distribution Pie chart shows that around 75.6% of loans was taken under 36 months term and 24.4% under 60 months term
  
- Results from Bivariate Analysis:
  
  1. **term vs loan_status** -->
     People opted for longer duration installments i.e. 60 months are going to default more, than people opted shorter duration i.e. 36 months
     From Term vs Loan Status Analysis, its clear that out of 8722 who opted for 60 Months as term 2230 has defaulted, means around 25.6 %, where as for those opted 36 Months only 2966 out of 
     26953 deafulted, thats just 11%
     
  2. **purpose vs loan_status** -->
     From Purpose vs Loan_status analysis, its clear that 27.8% of loans taken for the purpose of small_business end up as defaulters. This might be because of the failure of the business.
     Another insight is that for loans taken under 60 months as term and purpose as eductional and small_business shows very high default rates of about 42%.
     
  3. **dti vs loan_status** -->
     From dti vs Loan Status analysis, binned in 2 different methods Equal Width Binning and Quantile Binning shows almost similar patterns, that as the dti increases chances of defaulting also 
     increases.
     
  4. **funded_to_income vs loan_status** -->
     Similar analysis was made from realtionship btw funded_to_income vs loan_status, binned in 2 different methods Equal Width Binning and Quantile Binning.
     From analysis of 2 binning method one can come to a conclusion that as the funded_to_income increases chances of defaulting also increases
     From plot generated using Equal Width Binning for funded_to_income vs loan_status, its clear that almost 31.1% of loans got defaulted whose funded_to_income ratio was above 0.52.
     
  5. **difference of funded_amnt and funded_amnt_inv vs loan_status** -->
     Analysising realtionship btw the difference of funded_amnt and funded_amnt_inv, and Percentage of defaulters in each segment, binned using Equal Width Binning technique shows very 
     interseting analysis.
     So if the difference btw approved amount from LC and amount funded by investors increases, means the tendency for that loan to deafult is very high
     For loans which had a difference in approved amount from LC and amount funded by investors greater than 21.6K, around 46.5% of such loans was defaulted

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.3.4
- NumPy - version 1.20.3
- Seaborn - version 0.11.2
- MatplotLib - version 3.4.3
- Plotly - version 5.7.0


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contact

Group Members--- 
- [@Aabhilipsa] - feel free to contact me!
- [@ALabeeb] 

<!-- Optional -->

<!-- ## License -->

## License

This project is open source and available without restrictions.




<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
