# Amazon_Vine_Analysis

## Overview

Amazon has a Vine product review program, where people pay a fee to receive goods from companies and then leave reviews of what they thought of the products. Amazon wants to run a test to see if the Vine program has any potential influence on whether or not the reviews are positive or not.

The following PySpark picture shows a dataframe of the reviews of Electronic equipment, as well as what kind of reviews are left and how many people thought the reviews were helpful.

![image](https://github.com/CharlesBootCamp/Amazon_Vine_Analysis/blob/main/Resources/Spark.png)

This next photo illustrates a cleaned dataframe that also explains whether each review involved a vine reviewer.

![image](https://github.com/CharlesBootCamp/Amazon_Vine_Analysis/blob/main/Resources/Vine%20Table.png)

## Results

This next photo reduces the amount of reviewed products down to products that have at least a total of 20 reviews.

![image](https://github.com/CharlesBootCamp/Amazon_Vine_Analysis/blob/main/Resources/Vine%20Vote%20Count.png)

This next photo shows only the reviews where at least half of the reviews were positive.

![image](https://github.com/CharlesBootCamp/Amazon_Vine_Analysis/blob/main/Resources/Vine%20Helpful.png)

This next photo shows only the reviews where the reviewers were Vine members.

![image](https://github.com/CharlesBootCamp/Amazon_Vine_Analysis/blob/main/Resources/Vine%20Paid.png)

This next photo shows only the reviews where the reviewers were not Vine members.

![image](https://github.com/CharlesBootCamp/Amazon_Vine_Analysis/blob/main/Resources/Vine%20Unpaid.png)

This next photo shows the total number of reviews, the number of 5-star reviews, and the percentages of the two types of reviews.

![image](https://github.com/CharlesBootCamp/Amazon_Vine_Analysis/blob/main/Resources/Vine%20Total.png)

1. How many Vine reviews and non-Vine reviews were there?

There were a total of 1,080 Vine reviews and 49,659 non-Vine reviews.

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Out of the 1,080 Vine reviews, 454 were 5 star reviews and out of the 49,659 non-Vine reviews, 23,034 were 5 star reviews.

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

  The Vine reviews had about a 42% 5 star percentage, where the non-Vine reviews had about a 46% 5 star percentage.

## Summary

The number of 5 star reviews was actually lower for Vine members than non-Vine members, leading to the conclusion that any potential bias in leaving a review is minimal at best.
