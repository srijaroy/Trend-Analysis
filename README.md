# Trend-Analysis
Trend Analysis of Precipitation Using Mann-Kendall and Sen's Slope Test
The "Trend Analysis of Precipitation Using Mann-Kendall and Sen's Slope Test" is a comprehensive analytical approach designed to assess and identify trends in precipitation data. This repository contains code implementing two widely used statistical tests: the Mann-Kendall test and Sen's Slope test.

Mann-Kendall Test:

The Mann-Kendall test is a non-parametric test used to detect trends in time series data.
It assesses whether there is a monotonic upward or downward trend in the precipitation data over a specified period.
The test is based on the ranks of data points and provides a p-value indicating the significance of the observed trend.
Sen's Slope Test:

Sen's Slope test is employed to quantify the magnitude of the detected trend.
It calculates the median of all slopes between data points, offering a robust estimate of the trend's direction and intensity.
The slope obtained from this test represents the rate of change in precipitation over time.
How to Use:
Input your precipitation data in a suitable format (e.g., CSV, Excel).
Utilize the provided code to conduct the Mann-Kendall and Sen's Slope tests on the dataset.
The results, including trend significance and slope values, will be generated and displayed, aiding in the interpretation of precipitation trends.
Dependencies:
Ensure that your environment includes necessary dependencies such as statistical packages (e.g., SciPy) and data manipulation libraries (e.g., NumPy, Pandas).
