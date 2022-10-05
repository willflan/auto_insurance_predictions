# Summary of Project — Auto Insurance Predictions

In this project, we analyze customer data for over 10,000 individuals with regards to auto insurance, aiming to predict whether or not a customer would generate a claim (i.e., be involved in an accident necessitating a payout) in a given year. The dataset from which we will build our predictive tools involves over 20 input variables, ranging from demographic to financial to historical — many customers have made claims in previous years. Some have made many claims.

Presumably, our goal is for the auto insurance company to turn a profit this year. Therefore, our strategy will err on the side of expecting more incidents than may actually occur, as while it may sound morbid, it is more fiscally prudent for the firm to account for slightly higher-than-expected risk than to do the opposite. In terms of data-science practicality, this means that false negatives are more threatening than false positives.

Roughly 80% of the data entries are tagged with two output variables: a binary flag that indicates whether or not the entry is associated with a claim and, for those that are indeed associated, a payout value in dollars. While building predictive capacity on the claim amounts is beyond the scope of this project, we will explore the data in great depth to predict the binary outcomes from multiple intellectual vantage points. Much of the content found in sections 3, 4, and 6 can be considered supplementary.

### Walkthrough
1. Acquire and inspect dataframes.
2. Clean data and create working variables.
3. Explore scatterplots of payouts vs. all input variables.
4. Quantify the qualitative and binary variables.
5. Analyze correlations between variables.
6. Experiment with a manual predictive approach.
7. Select key evaluative metric for binary classification.
8. Generate final results with a machine-learning model.

Let's hit the road!
