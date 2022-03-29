# Amazon_Vine_Analysis
## Overview of Analysis
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. In this project, I had access to approximately 50 datasets, and chsoe to analyze the Video Game Reviews Dataset. I used PySpark to perform the ETL process to extract the dataset, transformed the data, connected to an AWS RDS instance, and loaded the transformed data into pgAdmin. Next, I used PySpark, to determine if there is any bias toward favorable reviews from Vine members in your dataset.

## Results
Below are the results of the analysis performed:

* Number of Vine reviews 
![This is an image](https://github.com/AleksKostrycka/Amazon_Vine_Analysis/blob/main/Resources/Total%20Paid%20Votes.png?raw=true)
* Number of non-Vine reviews
![This is an image](https://github.com/AleksKostrycka/Amazon_Vine_Analysis/blob/main/Resources/Total%20Unpaid%20Votes.png?raw=true)
* Number of Vine reviews with 5 stars
![This is an image](https://github.com/AleksKostrycka/Amazon_Vine_Analysis/blob/main/Resources/paid%205%20star%20reviews.png?raw=true)
* Number of non-Vine reviews with 5 stars
![This is an image](https://github.com/AleksKostrycka/Amazon_Vine_Analysis/blob/main/Resources/unpaid%205%20star%20reviews.png?raw=true)
* Percentage of Vine reviews with 5 stars
![This is an image](https://github.com/AleksKostrycka/Amazon_Vine_Analysis/blob/main/Resources/percentage%20of%20paid%205%20star%20review.png?raw=true)
* Percentage of non-Vine reviews with 5 stars
![This is an image](https://github.com/AleksKostrycka/Amazon_Vine_Analysis/blob/main/Resources/percentage%20of%20unpaid%205%20star%20reviews.png?raw=true)

## Summary

The results above represent a bias toward paid 5 star reviews. 51% of the reviews in the Vine program were 5 stars. 39% of the non-Vine reviews were 5 stars. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyze the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews to further determine the structure and insight that the data represents
