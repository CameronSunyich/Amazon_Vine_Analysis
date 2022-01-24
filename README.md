# Amazon_Vine_Analysis
![image](https://user-images.githubusercontent.com/90425412/150731023-4625ace8-08b4-4773-900a-dafc0a813280.png)

## Overview of the Vine Program Analysis:

Pick one of the 50 datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in chosen dataset.
The dataset chosen for this Challenge is Kitchenware

url link: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Kitchen_v1_00.tsv.gz

## Results:

Paid Reviews
- 1,207 total paid vine user reviews
- 509 total of paid five star reviews
- 42.17% paid reviews

Unpaid Reviews
- 97,839 total non-vine user reviews
- 45,858 total of non-vine user five star reviews
- 46.87% non-vine user review

## Summary:
The results above showed both types of reviews were split nearly in half. When comparing the percentage of five-star reviews the results were very similar. This points to the possibility that there is no bias for user types.
However, there are a few things to note about this data. It seems that there is an equal influx of reviews from each user type. There is a far greater amount of non-vine users reviewing overall. This means non-vine users have a larger sway on the star status of an item compared to Vine users.
Given the data, it is not clear if there is bias or not given the huge difference in types of users. I would recommend a further investigation of how star reviews vary for each customer type. As well as, the probability distribution. That way there can be a better look into a possible bias for users.
