# Amazon_Vine_Analysis

## Overview of the analysis: 
Using your knowledge of the cloud ETL process, you’ll create an AWS RDS database with tables in pgAdmin, pick a dataset from the Amazon Review datasets, and extract the dataset into a DataFrame. You'll transform the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Then, you'll upload the transformed data into the appropriate tables and run queries in pgAdmin to confirm that the data has been uploaded. Using PySpark, you’ll determine if there is any bias towards reviews that were written as part of the Vine program. For this analysis, you'll determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.


## Results:

- How many Vine reviews and non-Vine reviews were there?
170 Vine reviews
37840 non-Vine reviews

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
65 Vine reviews were 5 stars
20612 non-Vine reviews were 5 stars

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
38% of Vine reviews were 5 stars
54% of non-Vine reviews were 5 stars

![Screen Shot 2022-09-27 at 1 00 20 PM](https://user-images.githubusercontent.com/107209737/192623832-43ccb9f4-ed68-4a17-8ec6-e3410a73fd86.png)


### Summary: 

Vine members did not show bias when rating their products. There was only about a 16% difference between Vine and non-Vine members. Vine members may be more strict with their reviews, therefore it would be beneficial to run additional analysis. For example, running all the data would give us more information instead of just running just the the total number of reviews, the number of 5-star reviews, and the percentage of 5-star reviews for the two types of review (paid vs unpaid).
