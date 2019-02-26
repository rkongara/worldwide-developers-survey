# worldwide-developers-survey
This is an analysis of developer survey data conducted by StackOverflow in 2017. Following steps are carried out.

An exploratory analysis (EDA) was done first to discover any relationships/connection between developers salary and career satisfaction, and also between career satisfaction/salary and other input parameters.
Applied clustering models to see how to group the respondents..
Then applied classification models to see whether the models would correctly classify as per the labels assigned by clustering models in the second step.
Lastly, ran regression models to estimate developers salaries based on the input variables.
Key findings from the analysis are outlined in Summary section at the end.
Note: Since salary values are provided in local currencies, the values are converted to a common global scale by using purchasing power parity index, in order to compare.

This is done keeping in mind that, while determining salaries in each country, cost of living is taken into account. So mere conversion of all local currencies to USD using currency exchange rate alone is not going to give true picture. For example, if a developer's salary is 100K USD in USA, it does not literally translate into Rs.7,000,000 salary (considering Rs70/USD) in India. Since cost of living is less in India, the equivalant salary would be $100,000 x 18 = Rs.1,800,000 or 18L (assuming 18 is prevailing PPP index of India).
