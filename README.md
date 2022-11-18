# amazon_vine_analysis

## Overview of Analysis

### Purpose

The analyst was asked to assess whether Vine sourced Amazon reviews had a bias towards more positive reviewing. The analyst used PySpark to assess whether the percentage of 5 star reviews was greater for Vine reviewers on a random sample of video game reviews. The code for the analysis may be found [here](https://github.com/cbeckler/amazon_vine_analysis/blob/main/Vine_Review_Analysis.ipynb).

### Results

![vine analysis results](https://github.com/cbeckler/amazon_vine_analysis/blob/main/Resources/vine_analysis.png)

* There were 94 Vine reviews and 40,471 non-Vine reviews.
* Vine had 48 5 star ratings, while non-Vine reviews had 15,663 5 star ratings.
* 51.1% of Vine reviews were 5 stars, while 38.7% of non-Vine reviews were 5 star.

## Summary

It appears there may be a positivity bias in the Vine reviews, as there was a difference of roughly 12.5% between the Vine 5 star rate and the non-Vine 5 star rate. However, this analysis should be interpreted with caution as there is a large difference in sample size between Vine and non-Vine reviews, and the Vine sample size is quite small.

An additional analysis that could shed light on the differences between Vine and non-Vine reviews would be to perform a T-test on the review scores to assess whether the means of the Vine and non-Vine scores differed significantly. This would include all scores, not just five star reviews. 

