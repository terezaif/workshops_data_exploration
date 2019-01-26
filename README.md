# workshops_data_exploration
The workshop is split into four parts
In the first part of the workshop the focus is on understanding basic the concepts of data exploration. What to look for in the data and what are the tools.
In the second part we go in more detail on distributions, we go through the most common distributions, how to spot them and what they mean.
In the third part we go through the NYC taxi dataset and explore data and clean and transform and see how this already helps with getting better models.
In the last part we will look at what we do with high dimensionality data and how PCA works and how we can use it.

## Part 1: Looking at the data

In summary and in detail. For summary look we have two main ways: histogram and 5 number summary, which is visualised as a boxplot. 

Boxplot are also useful for comparing many groups of data or time series groups.

In Exercise 1 pick a dataset from the [datasets](part_1/datasets) folder and calculate: min, max, median and quartiles and draw a boxplot. What does it look like? 

Do it now in Python by following the notebook in [Data Summaries](notebooks/part_1/data_summaries.ipynb)

Looking at the data in detail we would need to plot the data differently, for example by using scatter plots.

Usually we try to compare a variable to another, for example height with age, this comparison can be measured via correlation.

For plotting different data distributions look at the notebook in [Data Details and Relationships](notebooks/part_1/visualise_relationships.ipynb).

## Part 2: Distributions

## Part 3: Case Study
We explore the [New York City Trip Duration](https://www.kaggle.com/c/nyc-taxi-trip-duration) dataset from kaggle and focus mainly on: 
- cleaning the dataset by filtering out outlier values
- exploring the relationship between two or more variables
  - how is the trip duration related to different locations in NYC
  - how does the trip duration change with time of week

You can also work directly on kaggle (if you create a kaggle account) by forking [this jupyter notebook](https://www.kaggle.com/hobilek/nyc-trips-amld).



## Part 4: PCA
