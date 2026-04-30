# bond_networks

Conduct EDA (Exploratory Data Analysis)

General exploratory analysis:

Distributions: How is the data distributed? Normal vs. Lognormal vs. Exponential, etc.
Noise: Is the information hidden by noise/random variability?
Scale: What is the scale of the numerical data? Do we need to transform certain columns?
Data Types: How many columns are numerical vs. categorical, etc.
Correlations: Are there similarities between the features? How strong are the relationships?
Cleaning: Are there inconsistencies in the data (related to formatting) that need to be addressed?
Join/merge: Determine the correct relationship between the different parquet files. How do we join the data?

Fixed Income specific questions:

How many government vs. corporate vs. other bonds are part of the data?
How are they distributed across regions?
What are the minimum and maximum yield/spreads/durations, etc.
Idenitify the realtionships between the different yield curves with respect to time horizon.
Are there any curves with an inverted yield curve? Are there similarities between these based on region, currency, classification, etc?
Verify the prices are inversely proportional to yield?
