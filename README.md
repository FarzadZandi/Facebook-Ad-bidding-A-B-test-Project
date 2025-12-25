# Facebook-Ad-bidding-A-B-test-Project

## Optimizing Ad Bidding: Facebook's A/B Test Story
About this directory
Features:
Impression: Number of impressions per ad.
Click: Numbers of clicks per ad.
Purchase: The number of products purchased after the click.
Earnings: Earning after purchase.

Database available at: https://www.kaggle.com/datasets/furth3r/facebook-ab-test-of-bidding-feature

Objective: To evaluate the performance of two ad bidding strategies, maximum bidding (control group) and average bidding (test group), in terms of their effectiveness at maximizing revenue per impression for Facebook advertisements.
Context: Evaluate the average revenue per impression for each bidding strategy via statistical tests. The need for such a test arises in a competitive digital advertising landscape where advertisers seek to maximize revenue while minimizing costs.

## Hypothesis Development:
Optimal bidding strategies suggest prioritizing impressions with a higher cost-effectiveness ratio, implying that non-linear and context-sensitive bidding algorithms perform better than traditional linear strategies (Zhang et al., 2014).
The near-optimal bidding strategy balances the value of impressions with costs under budget constraints, achieving significant improvements in campaign efficiency over constant bidding approaches (Tunuguntla and Hoban, 2020).
Maximum bidding strategies may overprioritize high-value impressions, whereas dynamic approaches like average bidding aim to maximize cost-effectiveness across a broader spectrum of impressions (Cai et al., 2017).

Hypothesis: The average bidding strategy (test group) will 		result in higher earnings, compared to the 		maximum bidding strategy (control group).<img width="3511" height="105" alt="image" src="https://github.com/user-attachments/assets/984047b3-40a0-46ff-8a3f-7fb6cf880c63" />

## Experiment Design
Users were randomly assigned to Control group and Test group, for 40 observation days, to eliminate bias.  This ensures internal validity by minimizing individual characteristics or external confounders (e.g., time-based effects).

Control Group: Users exposed to the Maximum Bidding strategy.
Test Group: Users exposed to the Average Bidding strategy.

### Metrics
Earnings: The revenue generated from user activities (e.g., purchases, ad conversions).  Measured as the sum of revenue per user based on their interactions after seeing the ad placement.
Clicks: The most important variable, which is the number of times users clicked on the advertisement or bidding placement.  Measured as the total number of clicks recorded on each day.
Purchases: The number of users who made a purchase after viewing the advertisement. 


### Other Key Features of the Design
Consistency: Ad exposure frequency and targeting remained constant across both groups.
Although randomization reduces bias, factors like seasonality or changes in user behavior might still influence results, which we account for in the analysis.

