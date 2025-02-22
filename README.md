# LoanPortfolioRiskAnalysis

## Risk Assessment and Analysis: Analyzing Loan Portfolio Risk for Daiz Bank

### Business Overview/Problem
Daiz bank’s challenge revolves around the management of their vast and diverse loan portfolio—a portfolio that has been the cornerstone of the bank's success. There is an immediate need to effectively assess and mitigate this multifaceted loan portfolio risk as this exposes the bank to constant threat of financial losses, regulatory hurdles, and reputational damage. The problem at hand is not just about safeguarding the bank's own interests but also ensuring the financial well-being of countless clients who have entrusted their dreams and aspirations to this esteemed institution.


Moreover, Daiz Bank's legacy risk assessment approaches have become increasingly inefficient in an era where speed and precision are paramount. Economic landscapes evolve rapidly, and the bank must adapt to ever-shifting market dynamics, regulatory changes, and emerging risks. The need of the hour is a dynamic, data-driven approach to risk assessment—one that not only identifies risks but also proactively mitigates them in real-time. To remain at the forefront of the financial industry, the bank must confront this challenge head-on, ushering in a new era of risk management that leverages the power of data analytics to safeguard its assets, reputation, and, above all, the trust of its clients

### Rationale for the Project

Risk analysis refers to the assessment process that identifies the potential for any adverse events that may negatively affect Daiz Bank in the process of giving out a loan. Conducting a risk analysis can help the bank determine whether they should approve a loan or financial application, and what actions they may need to take to protect their interests. This type of analysis facilitates a balance between risks and risk reduction. 

 
Risk analytics provides the tools and methodologies to analyze vast datasets, identify hidden patterns, and extract actionable insights in real-time. Unlike traditional methods that rely on historical data, risk analytics offers the advantage of adaptability. It can continuously process incoming data, enabling the bank to respond promptly to shifting market dynamics, economic indicators, and emerging risks. By harnessing the predictive power of analytics, the bank can proactively identify potential trouble spots within the portfolio, enabling timely interventions that mitigate losses and uphold the institution's financial health.
 

Risk analytics enables the bank to differentiate between high and low-risk clients and tailor its lending strategies accordingly. For clients, this means fairer loan terms, while for the bank, it translates into a more diversified portfolio. In essence, it allows the bank to strike a balance between profitability and risk exposure, ensuring long-term financial sustainability.

 
Lastly, risk analytics isn't just about managing risk; it's also about optimizing opportunities. By delving deep into the data, Daiz Bank can identify underserved markets, customer segments with growth potential, and innovative lending products. This proactive approach doesn't just shield the bank from potential losses; it propels it forward into a future where data isn't just a tool for risk mitigation, but a catalyst for growth.

### Aim of the Project
This project carries a lofty mission: to revolutionize the bank's approach to loan portfolio risk assessment. Our endeavor is rooted in the belief that data analytics, powered by advanced tools like Power BI, holds the key to unlocking unparalleled insights. These insights will not only empower the bank to make more informed lending decisions but also to optimize their risk management strategies. 

 
The bank’s aim is not merely profitability, but the creation of a resilient and diversified portfolio that thrives in the face of uncertainty, reduces credit losses, ensures compliance with ever-evolving regulations and more importantly, propels the bank forward into a future where data isn't just a tool for risk mitigation, but a catalyst for growth and innovation.

### Data Description
Note: A default on a loan occurs when payments are missed for a specified period, and it has been established that the loan is no longer going to be repaid. Arrears, are payments that are late, delayed or missed but where the borrower has every intention of making the payments later.

The bank has a database with 1500 rows of expense information for analysis, with the following attributes:

 
✓ Loan ID: A unique identifier for each loan in the portfolio.

✓ Borrower ID: A unique identifier for each borrower associated with the loan.

✓ Borrower Name: The full name of the borrower.

✓ Gender: The gender of the borrower.

✓ Borrower Age: The age of the borrower.

✓ Marital Status: The marital status of the borrower.

✓ Borrower Address: The address of the borrower.

✓ Borrower Email: The email address of the borrower.

✓ Borrower Phone Number: The phone number of the borrower.

✓ Loan Amount: The amount of money borrowed by the borrower.

✓ Loan Type: The type of loan, such as personal loan, mortgage, auto loan, or commercial loan.

✓ Interest Rate: The annual interest rate charged on the loan.

✓ Loan Term: The duration of the loan, in years.

✓ Loan Status: The status of the loan, such as "Paid Off," "Defaulted," or "In Arrears."

✓ Credit Score: The credit score of the borrower, which reflects their creditworthiness.

✓ Income: The income of the borrower.

✓ Employment Status: The employment status of the borrower, such as "Employed," "Self-Employed," or "Unemployed."

✓ Loan Origination Date: The date when the loan was initially issued.

✓ Loan Paid Date: The date when the loan was paid off or settled.

### Tech Stack
The data analysis for this project will be carried out Power BI. 


✓ Data Importation: Import the data into the environment.

✓ Data Cleaning and Manipulation

✓ Data Exploration and Analysis.

✓ Data Visualization.

### Project Scope
✓ Data Importation & Cleansing: Import data into the power BI  environment and cleanse it by identifying and rectifying errors, missing values, and inconsistencies in the data to ensure its accuracy and reliability.

✓ Exploratory Data Analysis: Power BI is utilized to generate descriptive statistics, such as summary statistics, distribution plots.

✓ Data Visualization: Power BI interactive dashboards and visualization capabilities enable the creation of charts, graphs, and heatmaps to uncover patterns and trends within the loan portfolio data.

✓ Reporting & Recommendation: Power BI facilitates the creation of customized reports for stakeholders, including bank executives, risk management teams, and regulators. These reports provide actionable insights and support data-driven decision-making.

### Project Activities
I imported the csv files into Power Query then carried necessary transformation like data cleaning, creating some needed columns for the analysis, created date table. Below is my Power query

![Power Query](https://github.com/adetonayusuf/LoanPortfolioRiskAnalysis/blob/main/Daiz%20Bank%20-%20Power%20Query.png)

Once I was done with Data cleaning and transformation, i loaded the tables into Power BI, then carried out data modelling by creating relationships between the loan dataset & othet sub tables and date table

![Modelling](https://github.com/adetonayusuf/LoanPortfolioRiskAnalysis/blob/main/Daiz%20Bank%20-%20Modelling.png)

I proceeded to carry the needed analysis by creating dashboards 

![Loan Portfolio Overview](https://github.com/adetonayusuf/LoanPortfolioRiskAnalysis/blob/main/Daiz%20Bank%20-%20Loan%20Portfolio%20Overview.png)


![Loan Status & Type Analysis](https://github.com/adetonayusuf/LoanPortfolioRiskAnalysis/blob/main/Daiz%20Bank%20-%20Loan%20Status%20%26%20Type%20Analysis.png)

### Insights
- Repayment Health: A repayment rate of 61.8% might be considered healthy depending on industry benchmarks. However, a delinquency rate of 21% and a default rate of 17.2%   
  are concerning, indicating a significant portion of the loan portfolio is at risk.
- The most loan and interest was seen in 2018, the most borrowed product is mortgage
- At $7,121,592 35-41 had the highest sum loan amount and was 17.5% higher than above 40, which had the lowest sum loan amount at $6,060,782
  35-41 accounted for 26.29% of sum loan amount
- In Arrears had $5,322,866 sum loan amount, Paid off had $16,790,481 and Defaulted $4,973,421, signifying that a number of borrowers has paid off their debt
- Mortgage is the most sought loan type followed by commercial loan
- Borrowers with credit score of 633-743 delayed in payment most and defaulted the most.
- Highest deaulted sum was in 2019
- Loan type with the highesr rate of default was commercial loan for 2018 and 2019 and mortgage 2020 and 2021

### Recommendation
- Enhanced Credit Score:The data indicates the borrowers with credit score between 633-743 have the highest delay and default rates. It may be beneficial to review and 
  adjust the credit scoring model to better prdict risk among borrowers within this range.

- Targeted Risk Management for Loan Types: Given the commercial loan had the highest rate of default iin 2018 and 2019and mortgage in 2020 & 2021, consider implementing 
  more stringent underwriting criteria for these loan types or revising their interest rate to better reflect the associated risk.

- Age Grouping Analysis: The age group o 35-41 has the highest sum loan amount and hence might be a critical demographic for business. However, ensure that this does not 
  lead to concentration risk. Diversifying the portfolio across different age groups could mitigate the risk.

- Product Focus Shift: With mortgages being the most borrowed product, ensure that the loan-to-value(LTV)  rates are conservative to reduce potential losses, especially if 
  property values decline.

- Delinquency and Default Intervention: The delinquency rate of 21% and a default rate of 17.2% are high. Early intervention strategies such as proactive communication and 
  restructuring options could help reduce these rates.

- Review Interest Rates: Since 2019 had the most loan and interest, review the interest rates from that year to determine if they're competitive and sustainable 
  particularly given the high default rate.

- Loan Performance Monitoring: Regularly monitoring loans that are "In Arrears" to prevent them from moving into default. Offer assistance such as repayment plans or n 
  financial counselling to help borrowers stay on track

- Financial Education: Offer financial literacy programs to borrowers, particularly in high risk categories to help them understand the importance of maintaining a good credit score and managing their loan effectively
