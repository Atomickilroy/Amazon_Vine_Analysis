# Amazon_Vine_Analysis
 
## Overview of Project
 
#### - *The goal of this project was to use PySpark to analyze if there is any bias present toward favorable reviews from Vine members. The Vine program is a paid service to persons who review Amazon products. By utilizing the ETL process to extract a Product Review dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. To then use PySpark to try to perform calculations to determine if or if not a bias can be determined.*
 
## Purpose
 
**The purpose of this project was to start learning tools that work hand and hand web visualizations:**
    -Define big data and describe the challenges associated with it.
    -Define Hadoop and name the main elements of its ecosystem.
    -Explain how MapReduce processes data.
    -Define Spark and explain how it processes data.
    -Describe how NLP collects and analyzes text data.
    -Explain how to use AWS Simple Storage Service (S3) and relational databases for basic cloud storage.
    -Complete an analysis of an Amazon customer review
 
##  - How many Vine reviews and non-Vine reviews were there?
### Total Vine Reviews - 613<br>
 
### Total non-Vine Reviews - 65,581
 
##  - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
### 5 Star Vine Reviews - 222<br>
 
### 5 Star non-Vine Reviews-30,543
 
##  - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
### Vine Percentage - 36.21% <br>
### non-Vine Percentage - 47.01%
 
__________________
 
# Analysis
Based on the results of this project, my initial recommendation would be to repeat these calculations across several additional datasets to determine if this was a one off example or not.
If a recommendation was needed based on this data set alone, the data presented indicated that more 5 star reviews are given across non-Vine programs. The reviews given by the Vine members appear to follow stricter guidelines. Being a paid service the data indicates no biased favorable reviews are present.
 
## Images of Results and Process:  
![map](https://github.com/Atomickilroy/Amazon_Vine_Analysis/blob/main/Images/Screenshot%202022-09-11%20211612.png)
 
![mobile](https://github.com/Atomickilroy/Amazon_Vine_Analysis/blob/main/Images/Screenshot%202022-09-11%20211720.png)
 
![mobile](https://github.com/Atomickilroy/Amazon_Vine_Analysis/blob/main/Images/Screenshot%202022-09-11%20211753.png)
 
![map](https://github.com/Atomickilroy/Amazon_Vine_Analysis/blob/main/Images/Screenshot%202022-09-11%20214157.png)
 
![mobile](https://github.com/Atomickilroy/Amazon_Vine_Analysis/blob/main/Images/Screenshot%202022-09-11%20214216.png)
 
![mobile](https://github.com/Atomickilroy/Amazon_Vine_Analysis/blob/main/Images/Screenshot%202022-09-11%20214228.png)
