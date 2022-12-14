# Amazon_Vine_Analysis
## Overview of the Analysis
The goal of this project was to analyze the Amazon Vine program to see if there is a bias toward favorable reviews from members of Vine. Pyspark was used to perform the ETL process to extract and transform the data, connect to an Amazon Web Service RDS and then load that data into pgAdmin. We used the data for US reviews on video games.
## Results
* There were 94 Vine reviews and 40471 non Vine reviews. 
* ![pic](https://github.com/peterthepage/Amazon_Vine_Analysis/blob/main/Resources/Capture1.PNG)
* There were 48 paid 5 star Vine reviews and 15663 non vine reviews. 
* ![pic2](https://github.com/peterthepage/Amazon_Vine_Analysis/blob/main/Resources/Capture2.PNG)
* Just over 51% were 5 star Vine reviews and 38.7% of non Vine reviews were 5 stars. 
* ![pic3](https://github.com/peterthepage/Amazon_Vine_Analysis/blob/main/Resources/Capture3.PNG)
## Summary
Vine reviews had a higher percentage of 5 star reviews at 51% versus non-Vine reviews at 39%. However, more data is needed from Vine reviews for it to be statistically significant, especially when comparing the size of the non-Vine reviews. Looking at the mean and median of the two datasets would give us a good idea of how similar these two datasets are. 
