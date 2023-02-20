# Amazon_Vine_Analysis
## Overview
### The purpose of this project is to detemine whether or not there is bias in reviews given from paid and unpaid users. The dataset I chose to handle was Amazon's Mobile Electronics Data. For this analysis, PySpark was used to perform the ETL (extract, transform, and load) process on the dataset. Furthermore, I connected to an AWS RDS instance in order to load the transformed data into pgAdmin and calculate different metrics.

## Findings
### Vine Users Summary: 
####
- Vine Users: 4
- Non-Vine Users: 1064 
### 5 Star Reviews Summary: 
####
- 5 Star Review from Vine Users: 1
- 5 Star Reviews from Non-Vine Users: 527
### % of 5 Star Review Summary: 
####
- % of 5 Star Reviews from Vine Users:  25 %
- % of 5 Star Reviews from Non-Vine Users:  49.5 %
## Analysis
### 
The percentage of 5 star reviews given by non-paid users is about twice as high as 5 star reviews given by paid users. Two possible explanations for bias in our data could be presented from paid users having higher standards or the fact that our data is derived from mobile data. Because our data is derived from mobile information, our sample could become more sensitive to factors such as age, race, ethnicnity, or income. More could be said if we generated sample statistics such as mean, median, IQR, etc...
