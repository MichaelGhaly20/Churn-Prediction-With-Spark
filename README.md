# Churn-Prediction-With-Spark
Churn estimation is of great importance for companies. According to McKinsey's research, fast-growing companies are expected to have low churn rates in order to maintain their profitability in a stable manner.

![spark](https://user-images.githubusercontent.com/59583421/156902389-5b36587c-c7c1-4002-928c-5855e0eefe0f.jpeg)

Apache Spark lets you process data in parallel. For example, suppose you have a data set of 1,000,000 rows. Let's use this dataset for machine learning. Let there be a combination of "label" and "text" in the dataset. We will give a text and determine which tag it is similar to with a classification algorithm. Normally it will be difficult to calculate within 1,000,000 data. However, with the spark architecture, we calculate the data in sets of 1000 by dividing it by 1000, for example, and calculate it much faster with an calculation such as the average of the set of 1000.

**1.It is fast**

Spark runs 100 times faster than Hadoop MapReduce, which is used for large-scale data processing. It can also reach this speed through controlled partitioning.

**2.Strong Caching**

The simple programming layer provides powerful caching and disk persistence capabilities.

**3.Real-time**

It offers Real Time computing and low latency due to in-memory computing.

**4.Language Support**

Spark offers high-level APIs for Java, Scala, Python, and R. You can use Spark in any of these four languages.
