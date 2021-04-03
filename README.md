# Amazon_Vine_Analysis

## Overview of the Analysis

In this project I had access to approximately 50 datasets. Each one contained reviews of a specific product, from clothing apparel to wireless products. I ended up going with toy reviews. I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and loaded the transformed data into pgAdmin. I then use PySpark to determine if there was any bias toward favorable reviews from Vine members in the dataset.

## Results

### Deliverable 1
  - Successfully extracted the dataset, transform the data, connected to an AWS RDS instance, and loaded the transformed data into pgAdmin.
  
  ![review_id_table](https://github.com/RyanWhited/Amazon_Vine_Analysis/blob/main/resources/review_id_table.jpg)

  ![customers_table](https://github.com/RyanWhited/Amazon_Vine_Analysis/blob/main/resources/customers_table.jpg)

  ![products_table](https://github.com/RyanWhited/Amazon_Vine_Analysis/blob/main/resources/products_table.jpg)

  ![vine_table](https://github.com/RyanWhited/Amazon_Vine_Analysis/blob/main/resources/vine_table.jpg)

### Deliverable 2

  - How many Vine reviews and non-Vine reviews were there?

  ![total_vine_reviews](https://github.com/RyanWhited/Amazon_Vine_Analysis/blob/main/resources/total_vine_reviews.jpg)

  - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

  ![vine_five_star](https://github.com/RyanWhited/Amazon_Vine_Analysis/blob/main/resources/vine_five_star.jpg)

  - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

  ![total_vine_reviews](https://github.com/RyanWhited/Amazon_Vine_Analysis/blob/main/resources/total_vine_reviews.jpg)


## Summary

Based on these results, it appears that there's no positivity bias for reviews in the Vine program as the percentage of 5-star reviews from Vine members was only 34% and for non-members 48%. 

Another analysis I would consider factoring in is filtering the verified_purchase column to make sure we're more accurate as we would on
