# Amazon_Vine_Analysis
## Overview of Analysis
Analyze Amazon reviews written by members of the paid Amazon Vine Program.  Determine if there is any bias toward favorable reviews from Vine members.

_Background:_ Numerical star ratings in customer reviews tend to be disporportionately positive.  Positivity bias most commonly occurs in the form of under-reporting bias where customers who write reviews are either greatly satisfied or greatly dissatisfied. (_Source:_ "Positivity Bias in Customer Satisfaction Ratings" https://dl.acm.org/doi/fullHtml/10.1145/3184558.3186579)

## Results
#### Total reviews
- Vine = 170

  ![YTotal](https://user-images.githubusercontent.com/90986041/148711003-80e1075a-6ee0-4137-bde8-87f7e74c4c72.png)

- Non-Vine = 37,840

  ![NTotal](https://user-images.githubusercontent.com/90986041/148711019-8c711759-14f7-4687-916b-0e3f44d8e013.png)

#### How many 5-star reviews?
- Vine = 65

  ![YFive](https://user-images.githubusercontent.com/90986041/148711280-f02805ca-b07c-4bf9-80eb-755968ecab9d.png)

- Non-Vine = 20,612

  ![NFive](https://user-images.githubusercontent.com/90986041/148711314-033ffb54-01b6-4bd8-a5db-544200422d03.png)

#### What percentage of the total reviews were 5 stars?
- Vine = 38.2%

  ![YPercent](https://user-images.githubusercontent.com/90986041/148711379-0d4d233c-5b26-45c8-8765-a118ed2673ce.png)

- Non-Vine = 54.5%

  ![NPercent](https://user-images.githubusercontent.com/90986041/148711400-846b5ad1-a2ea-4956-b93e-f808b5334b4e.png)


## Summary
Based upon the low percentage (38.2%) of 5-star ratings from Vine program members, there does not appear to be positivity bias for reviews in the Vine program.  

_Additional Analysis:_ The above results include ratings of products that may not have been actually purchased.  Determine if actual purchases change the 5-star rating percentages of reviews in the Vine program (include filter: verified_purchase = "Y").
___

_Dataset_:  Amazon Review Datasets: Pet Products

_Application:_ PySpark

_Analyst_: S. Lewer
