# Welcome to Computer Learning Using Big Data! 

Data come from a wide variety of sources: from physical sensors, social media posts, academic survey responses, polling responses, video feeds, and more. How do we make sense of all that data? How can we learn from the data to better understand our world? This course will introduce computer programming tools that you can use to handle large data sets, visualize the data, and teach the computer how to learn from the data to make predictions about the future.

## Course Tools

We will be programming in [Python](https://www.python.org/) with an alternative track in `R`. No prior programming experience is necessary. You will learn everything you need to know as we go through the course of the semester. If you are familiar with a Python/R distribution, you may install the necessary packages as you go along.

Another alternative is to use [SageMath Cloud](https://cloud.sagemath.com) for the programming, visualization, and machine learning for this course. All of the packages and tools we use are already installed.

## Homework

There will be regular homework assignments that will be given at the end of each class period. Learning is best accomplished by doing, so give the assignments a try.

## Course Project

There is also a final project component to the course. The goal is to join all of the tools and techniques together into a single machine learning project.

### Where to get data
We will spend quite a bit of time looking for public data as we get going in this class. Here are a couple of places to look for data sets to work with:
* The UCI repository: https://archive.ics.uci.edu/ml/datasets.html
* Kaggle Public Datasets: https://www.kaggle.com/datasets
* Ceasar's repository: https://github.com/caesar0301/awesome-public-datasets

You will need to dig into some of these sources to find data sets that you are interested in working with.

## Course Schedule

| Class |Topic|
|:-:| :-----|
|01|Big Data Ingesting: CSVs, Data frames, and Plots: [Python](/Class01/Class01.ipynb) / [R](/Class01/Class01-R.ipynb)
|02|ML Models: Linear regression + Validation: [Python](/Class02/Class02.ipynb) / [R](/Class02/Class02-R.ipynb)
|03|[Big Data Cleaning: Data Transformations](/Class03/Class03.ipynb) (with [Supplemental Work](/Class03/Class03_supplement.ipynb))
|04|[ML Models: Naïve Bays + Evaluation Metrics](/Class04/Class04.ipynb)
|05|[Big Data Enrichment: Joining and Grouping data](/Class05/Class05.ipynb)
|06|[ML Models: SVM + Overfitting](/Class06/Class06.ipynb)
|07|[ML Models: Decision Trees](/Class07/Class07.ipynb)
|08|[ML Techniques: Outliers](/Class08/Class08.ipynb)
|09|[ML Models: Clustering](/Class09/Class09.ipynb)
|10|[ML Techniques: Feature scaling](/Class10/Class10.ipynb)
|11|[ML Techniques: PCA](/Class11/Class11.ipynb)
|12|[ML Models: Logistic Regression](/Class12/Class12.ipynb)
|13|[ML Models: Neural Networks](/Class13/Class13.ipynb)

## The Three Learning Principles

### 1. Occam's Razor

The general idea from Occam is: _Frustra fit per plura quod potest fieri per pauciora_ (It is futile to do with more things that which can be done with fewer). We will strive to cut out unneeded details from our models again and again and again over the course of the semester. We will see that, as a rule of thumb, the simplest model that fits the data is also the most plausable and will tend to have the best out-of-sample performance. We will look at how the model's free parameters affect the in-sample and out-of-sample performance.

### 2. Sampling Bias

No matter how good your model is, the real-world performance ultimately depends on the data you use to train the model. If the data have an inherent bias, then the model's predictions will reflect that bias. We will continually ask ourselves: "Where do the data come from?" and "How are they collected?" The more we understand about the quality of the data, the more we will know about their predictive power.

### 3. Data Snooping

This principle is, perhaps, the most challenging. If a data set has affected any step in the learning process, its ability to assess the outcome has been compromised. We will work hard to separate out "testing" data and lock it away as soon as possible in the learning process. This will help us combat the problems that arise through data snooping.
