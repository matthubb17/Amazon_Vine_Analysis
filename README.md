# Amazon_Vine_Analysis

## Project Overview:

The goal of this project was to use PySpark in order to extract a dataset from Amazon reviews. The dataset that I chose was the below dataset:

* https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Sports_v1_00.tsv.gz

## Resources:

**Deliverable 1:** [Amazon_Reviews_ETL.ipynb](https://github.com/matthubb17/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_ETL.ipynb)

**Deliverable 2:** [Vine_Review_Analysis.ipynb](https://github.com/matthubb17/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb)


**Software:** Google Colab, PySpark, Amazon Web Services (AWS), PgAdmin4


## Results:

The figure below is the summary showing all Vine and non-Vine reviews within the Sports vi dataset. It also shows the number of 5-star reviews along with the percentage of 5-star reviews.

![Image 1](https://github.com/matthubb17/Amazon_Vine_Analysis/blob/main/Images/Summary%20Image.png)

* Looking below we can see that there were 334 Vine reviews and 61,614 non-vine reviews

![Image 2](https://github.com/matthubb17/Amazon_Vine_Analysis/blob/main/Images/Total%20Reviews%20for%20Vine%20and%20Non-Vine.png)

* There were 139 5-star Vine reviews and 32,665 non-vine 5-star reviews

![Image 2](https://github.com/matthubb17/Amazon_Vine_Analysis/blob/main/Images/Total%205-star%20Reviews%20Vine%20and%20non-vine.png)

* The percentage of 5-star Vine reviews was 41.6% and there were 53.0% non-vine 5-star reviews

![Image 3](https://github.com/matthubb17/Amazon_Vine_Analysis/blob/main/Images/%25%20of%205-star%20Reviews%20Vine%20and%20non-vine.png)
