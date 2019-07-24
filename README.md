# datamining
python (pandas) examples
This repository currently used to store 2 datamining projects written in python, including using features from pandas package, 
e.g. DataFrames. 

1. "Military spending" project ingests data from Stockholm International Peace Research Institute (SIPRI) Military Expenditure Database.
The data is filtered on countries of interest years of interest (2010 to 2017). 
Multiple facets of the data are investigated. Overall (absolute) military spending per country. Miltary spending per country as 
a percentage of the countries' GDPs. Spending as a ratio of population. Head to head comparisons and comparisons over time
of spending among the countries are depicted both numerically and graphically. 

2. "DistrZIPIncome" project is a start at looking at how income (as measured by Adjusted Gross Incomes in tax returns), is distibuted across the Legislative Districts of the House of Delegates for Virginia. The project merges data from 3 sources. (1) The IRS has AGI data per zipcode. (Basically, AGI is categorized into ranges based on amounts and the number of returns filed per category is published).
(2) Census provides correspondence of census tracts per zipcode, (3) and census tract information can be linked to Legislative Districts. 
