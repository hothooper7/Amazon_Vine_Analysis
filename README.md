# Amazon_Vine_Analysis
This analysis is of the Amazon Vine program, a program that allows manufacturers and publishers to receive reviews for their products.  Specifically, this project will aim to see if there is any bias for favorable reviews between Amazon Vine members and non-members.  Certain companies pay a fee to Amazon and provide products to Vine members who are required to write a review after receiving the product.  


## The Data
The dataset that was used is from the Amazon Review datasets page, and the category chosen was video games.

## Results

1. How many Vine reviews and non-Vine reviews were in the dataset?

As demonstrated in the below image, there are 104 Vine (paid) reviews and 65,274 non-Vine (unpaid) reviews in the dataset.

![Vine vs  Non Vine Reviews 2](https://user-images.githubusercontent.com/100809925/175819310-4c80de29-4cb4-4eb4-8b77-b06bae905d16.jpeg)

2. How many Vine reviews and non-Vine reviews were 5 stars?

As demonstrated in the below image, there are 48 Vine (paid) 5 star reviews and 20,439 non-Vine (unpaid) 5 star reviews in the dataset.

![5-Star Vine vs  5-Star non-Vine](https://user-images.githubusercontent.com/100809925/175818949-6b3f6c33-b94b-4524-810d-ed963d1aa0a2.jpeg)

3. What percentage of Vine reviews and non-Vine reviews were 5 stars?

AS demonstrated in the below image, 0.23% of 5 star reviews were from Vine (paid) subscribers, and 99.77% of 5 star reviews were from non-Vine (unpaid) subscribers.  

![Percentage of 5 star reviews](https://user-images.githubusercontent.com/100809925/175819243-6825a2a9-64b9-4bcb-b10e-03bc93705f0f.jpeg)

## Summary

Based on my analysis, there does not seem to be any positivity bias for reviews in the Vine program.  Since the total number of 5 star reviews from Vine and non-Vine members was proportionate to the amount of subscribers in each group, it can be inferred that the paid subscriptions do not lead to better reviews.  An additional test on this dataset that would be insightful would be to see if there is any difference in the figures when the data is not filtered.

To see if this research is an anomaly or if there doesn't exist bias between subscription types, this analysis should be performed on most or all of the various Amazon datasets.  To repeat the process would be very easy since the code has already been written and only a few changes would be necessary.  
