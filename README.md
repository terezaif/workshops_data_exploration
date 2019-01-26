# workshops_data_exploration
The workshop is split into four parts
In the first part of the workshop the focus is on understanding basic the concepts of data exploration. What to look for in the data and what are the tools.
In the second part we go in more detail on distributions, we go through the most common distributions, how to spot them and what they mean.
In the third part we go through the NYC taxi dataset and explore data and clean and transform and see how this already helps with getting better models.
In the last part we will look at what we do with high dimensionality data and how PCA works and how we can use it.

## Part 1: Looking at the data [Slides](part_1/slides_1.pdf)

In summary and in detail. For summary look we have two main ways: histogram and 5 number summary, which is visualised as a boxplot. 

Boxplot are also useful for comparing many groups of data or time series groups.

In Exercise 1 pick a dataset from the [datasets](part_1/datasets) folder and calculate: min, max, median and quartiles and draw a boxplot. What does it look like? 

Do it now in Python by following the notebook in [Data Summaries](notebooks/part_1/data_summaries.ipynb)

Looking at the data in detail we would need to plot the data differently, for example by using scatter plots.

Usually we try to compare a variable to another, for example height with age, this comparison can be measured via correlation.

For plotting different data distributions look at the notebook in [Data Details and Relationships](notebooks/part_1/visualise_relationships.ipynb).

## Part 2: Distributions [Slides](part_2/distribution_presentation.pdf)
Understanding of the data distribution is importat, since it is empovering better models, proper tests, easier modelling process. For following 5 distributions we will show histogram, violine plot and qq-plot where it makes sense. We will explain how to make hypothesis about the distribution family based on the information from the graphs.
Distributions are:
- Normal (Continuous, symmetrical, symmetrical tails, no shift, no skew, two-sided)
- Student (Continuous, similar to normal, but has fatter tails)
- Binomial (Descrete, symmetrical, with a lot of trials resembles normal distribution)
- Poisson (Descrete, not symmetrical, one-sided)
- Exponential (Continuous, not symmetrcial, one-sided, based-of-poisson)
- Weibull (Continuous, shape-shifting, based-of-exponential/poisson)

As the excercise plot the graphs for the given data sets (dataX from the last 2 cells of the notebook) and try to identify the distribution behind it.


## Part 3: Case Study
We explore the [New York City Trip Duration](https://www.kaggle.com/c/nyc-taxi-trip-duration) dataset from kaggle and focus mainly on: 
- cleaning the dataset by filtering out outlier values
- exploring the relationship between two or more variables
  - how is the trip duration related to different locations in NYC
  - how does the trip duration change with time of week

You can also work directly on kaggle (if you create a kaggle account) by forking [this jupyter notebook](https://www.kaggle.com/hobilek/nyc-trips-amld).



## Part 4: PCA [Slides](part_4/Exploratory%20Data%20Analysis%20Workshop.pdf)

Principal Component Analysis is a unsupervised machine learning technique used for multivariable exploratory data analysis and dimensionality reduction.

Even though is a well established technique, its foundations are still explained in broken parts in the internet. This tutorial intends to join all the theoritical side and show how it connects with the practical applications.

Notebook [https://bit.ly/2UhS65O](https://bit.ly/2UhS65O)
