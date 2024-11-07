# A/B Testing using p-value and t-value

This project demonstrates the process of performing **A/B Testing** for comparing two versions of a product or service using statistical analysis. The goal is to determine whether there is a significant difference between two groups (A and B) using **p-value** and **t-value** as the key metrics for hypothesis testing.

## Project Overview

A/B testing is a controlled experiment comparing two versions (A and B) to evaluate which one performs better. In this project, we perform A/B testing using the following steps:

1. **Data Preparation**: 
   - Loading and preprocessing the data for both groups (A and B).
   - Ensuring that the data meets the assumptions for t-tests (e.g., normal distribution, equal variances).

2. **Hypothesis Testing**: 
   - Setting up the null and alternative hypotheses:
     - **Null Hypothesis (H0)**: There is no significant difference between the two groups.
     - **Alternative Hypothesis (H1)**: There is a significant difference between the two groups.
   - Performing a **t-test** to calculate the **t-value** and **p-value**.

3. **Interpretation**: 
   - Interpreting the p-value to decide whether to reject or fail to reject the null hypothesis.
   - Understanding the **t-value** to assess the magnitude of the difference between the groups.

4. **Visualization**: 
   - Visualizing the A/B test results using plots to help in decision-making.

