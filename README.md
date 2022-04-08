# Amazon_Vine_Analysis

## Overview of the Analysis
Purpose: To see if there is a bias in amazon review scores by analyzing the difference between Vine reviews, which are paid, and non-Vine reviews, which are unpaid.

## Results
- There were 60 total Vine reviews and 14,477 non-Vine reviews.
- There were 34 five-star vine reviews and 8,212 non-Vine reviews.
- 56.6% of Vine reviews and 56.7% of non-Vine reviews were five-star.

## Summary
From the analysis done thus far, there is not enough evidence to suggest a positivity bias for Vine reviews in the musical instruments category. The ratio of five-star reviews to total reviews for Vine and non-Vine almost identical. Furthermore, there were only 60 Vine reviews, compared to a whopping 14,477 non-Vine reviews; with such a huge difference in sample sizes, it is really hard to compare the two groups. To further look for bias, I would take product_id and product_title from the original dataset and bring them into the vine dataframe. After sorting down to the two dataframes, vine and non-Vine, I would groupby product_id, and aggregate the average review and review count for both. Then I would do an inner join on both dataframes and analyze. All that said, I do not expect a different result.