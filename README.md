## Volatility study 

Below you are given four commodity prices, ranging from 2023-01-01 to now, at a granularity of one minute. The purpose of this study is to analyze the historical volatility of these four commodities, and forecast one day ahead volatility to give your trader an indication of what strategies he should use tommorrow. 


# Part 1.
a) Give an overview of each of the descriptive statistics for each of the commodities, in particular, provide the first four moments and the 25th, 50th, and 75th quantiles.

b) Which distribution (normal, student-t, cauchy) fits the data best? Please back your choice by statistical tests.

c) Build a function that generates a plot of a specific distribution against the empirical data.

c) Are the commodities stationary?

d) Below you are provided a Quantile-Quantile plot for the Cauchy distribution versus the empirical distribution. 


How do the tails of the empirical distribution of your asset behave versus the theoretical distriubtion? 

# Part 2.
a) Fit a GARCH(1, 1) model to each of the assets and forecast one period ahead.

b) How does your model perform compared to the benchmark of the previous days 5 minute realized volatility?
