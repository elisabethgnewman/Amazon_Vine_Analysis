# Amazon_Vine_Analysis

## Overview of Analysis
The purpose of this analysis was to use what we learned in Module 16 about Big Data to work with AWS, Colab, and pgAdmin. 

In my analysis, I pulled the AWS US Shoes data and created four different dataframes to display: customer information (customer ID and count of instances), product information (product ID and title), review information (review ID, customer ID, product ID, and date), as well as a vine table to show the review ID, star rating, helpful votes, vine, and verified purchase).

![image](https://user-images.githubusercontent.com/88783255/145735912-f6461c25-6c4e-429a-a972-c4598318caee.png)

The vine dataframe will be the most helpful with our analysis because it's providing detailed information about each review.

## Results
There were 2,639,935 reviews with 5 star ratings:

![image](https://user-images.githubusercontent.com/88783255/145736560-63662644-0855-4071-bda7-b95eead8a192.png)

## Summary

There is likely a positivity bias, given the vast amount of 5 star ratings in this data; however, the data doesn't suggest it is because of vine vs. non-vine reviews. When a review is required, I would assume that the reviewer is more likely to give a 5 star review. In this case, 

![image](https://user-images.githubusercontent.com/88783255/145737496-6c35f24e-9206-4fc4-86d2-b2b499a400ff.png)

