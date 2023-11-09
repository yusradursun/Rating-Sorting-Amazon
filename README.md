# Rating Product & Sorting Reviews in Amazon
This dataset, which includes Amazon product data, includes product categories and various metadata. The dataset consists of the product with the most reviews in the electronics category has user ratings and reviews.

# Business Problem
One of the most significant problem in e-commerce is the correct calculation of the points given to the product after sales. The solution to this problem means providing greater customer satisfaction for the e-commerce site, prominence of the product for the sellers and a smooth shopping experience for the buyers. Another problem is to order correctly of the comments given to the products. Since become prominent of misleading comments affect the sale of the product directly, this will cause both financial loss and loss of customers. In the solution of these 2 basic problems, while the e-commerce site and the sellers will increase their sales, the customers will complete the purchasing journey without any problems.

There are 2 aims of the project:

Finding the best average rating calculation of the product
Sorting reviews in a logical order
The approach will be:

Sorting average with the effect of time: The dataset will be separated into timeframes, and each timeframe will have a different weight and an upvote/downvote trend will be observed. (Time-Based Weighted Average)
Sorting helpful reviews by upvote/downvote numbers: Best reviews will be revealed with different approaches to upvote and downvote numbers. (Up-down difference, average rating, Wilson lower bound)

# Dataset Variables
This dataset, which includes Amazon product data, includes product categories and various metadata. The dataset consists of the product with the most reviews in the electronics category has user ratings and reviews.

reviewerID: User ID
asin: Product ID
reviewerName: User name
helpful: Helpful review
reviewText: Review text
overall: Product rating
summary: Review summary
unixReviewTime: Review time
reviewTime: Raw review time
day_diff: Number of days since review
helpful_yes: The number of times the review was found useful
total_vote: Number of votes given to the review
