# Amazon_Vine_Analysis

## Objective
Our first objective for this project was to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal will be to use PySpark to perform a statistical analysis of selected data.
The overall purpose was to analyze Amazon reviews written by members of the paid Amazon Vine program.



### Results
1. We found that there are 21 vine reviews and 7689 non vine reviews of jewlery products on the amazon website.
2. 11 out of the 21 vine reviews are 5-star reviews while 4444 out of the 7689 non vine-reviews are 5-stars.
3. 52.38% of the vine reviews are 5-stars. 57.79% of the non vine jewlery reviews are 5-stars.

### Summary
 This dataset was not a good dataset to choose in order to see if there is a positive bias with the Vine program as there were no Vine reviews in the dataset. There doens't seem to be a positivity bias for reviews in the Vine program. We can conclude that by comparing vine member reviews with non vine member reviews. As noted above, the percentage of 5 star reviews is higher for non vine members than it is for vine members. That shows the vine members were honest in their reviews and not influenced by money paid to them. Moreover, in order to make our statement more accurate, we could filter the data out for verified purchases. That would make the reviews selected more pertinent to our research questions and hence will yield more accurate results.
