# KPMG-Sprocket-Central

In October 2021, I was a Data Analyst Intern with KPMG, and this is the capstone project to test and demonstrate the skills i have gained during this period.

## Project goal: To find the top 1000 customers and drive campaigns to them

## Company Overview

Sprocket Central Pty Ltd, a medium-sized bike and cycling accessory company ccontacted me, an intern in KPMG's Lighthouse & Innovation Team. Sprocket Central Pty Ltd is interested in finding out more about the knowledge KPMG's Analytics, Information & Modeling division has to offer. I emphasized on the domain knowledge of KPMG. In particular to discussed how the group will use the dataset analysis to help Sprocket Central Pty Ltd expand its operations.

Sprocket Central Pty Ltd needs assistance with its customer and transaction data most of all. The company has a sizable dataset about its clients, but the team doesn't know how to use it to optimize its marketing plan. That is why i am here...

The company provided us with 3 datasets:
*	Customer Demographic 
*	Customer Addresses
*	Transactions data in the past 3 months
The dataset was downloaded from their website anad has been uploaded into this file. It can also be found here: https://docs.google.com/spreadsheets/d/1roP8lZ3WVOdcbkhmKZb5Gu0KjffwF7qN/edit?usp=sharing&ouid=104179283946869942722&rtpof=true&sd=true

when i asked the Associate Director for some ideas to enhance the analysis, she expressed that the likelihood that i can use the dataset to spur firm growth increases with the dataset's quality. These were her words:
> "The importance of optimizing the quality of customer datasets cannot be underestimated" 

So i decided to start the preliminary data exploration  using **Microsoft Excel**  to identify ways of improving the quality of Sprocket Central Pty Ltd’s data. Working on the various sheets, i had the follwoing:

CUSTOMER DEMOGRAPHIC SHEET
1.	No last name was recorded for a customer in  the last name column
2.	On Gender, there are data with “M” instead of Male, there are some with femal instead of female. Then there was a data that was “f” instead of female, also there was “U” as gender which one cannot count or ascertain as either male or female. So it was needful to remove the “U” and then have a uniform input for male and female. 
3.	There was a record of 122 years. I think it’s an error, so I removed it, so that it doesn’t alter the data set. The Date of birth column was used to get the appropriate ages.
4.	There were some blank values on the Job title column
5.	The deceased were also included in the dataset, so I decided to remove it.
6.	The column named default had very unclean and misleading information which we cannot fathom or use. So it is best if it is removed.

CUSTOMER ADDRESS SHEET
1.	On the column named State. Some data weren’t well inputted, so a little cleaning was done to make the states have the same format.
2.	The blank spaces in the online order  column were removed
3.	The blank spaces on the brands columns too were removed
4.	On the price list column, no currency was attached to it, so I had to input the currency to dollars.
5.	Product first sold date column wasn’t properly recorded, so it will be changed to a short date format to enhance readability and understanding.
6.	No extra information was given with respect to the profits or loss, so we added a column known as Profit as made the calculations.

NEW CUSTOMER LIST
1.	On the Gender column, a value ‘U’was inputtedin addition to male and female, so I removed it.
2.	On the column with past three years bike related purchases the values were written as text format instead of numbers, so I converted them to numbers.
3.	In the Job title column, there  were blank spaces, so we will have to remove them
4.	In the Post Code column, the values were saved as text format, so we need to change them to number.
5.	In the Property valuation column, the values were saved as text format, so we need to change them to number 
6.	There were hidden columns between P and V, they were opened and examined and the values were converted from general or text to numbers and made to be in 3 decimal places. They had formulas that showed that they are connected so there was no need to remove them
7.	Two columns had same values, so one was deleted.

The essence of thorough cleaning and evaluation of the data sets (reformatting, deleting duplicate columns, removing unsure data) is to ensure that our data has quality, is accurate, complete, consistent, unique, valid, unique, current and relevant to our analysis. 
A clean data will enable us carry out analysis that will make smarter business decisions based on facts, not instinct. Will also enable us win new customers and reduce business risk.

