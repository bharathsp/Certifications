# Taming Big Data with Apache Spark 4 and Python.pdf

## Certificate no: UC-6caea177-a20c-4576-8951-059e81364492
## Certificate url: ude.my/UC-6caea177-a20c-4576-8951-059e81364492

![Udemy - Taming Big Data with Apache Spark 4 and Python](https://github.com/user-attachments/assets/5011fc52-3619-494a-8140-34e41ddbb640)

---

### 🌟 **Learnings from “Taming Big Data with Apache Spark 4 and Python”**

* 🚀 **Spark 4 Features** – Explore the latest capabilities of Spark 4.
* 📘 **Introduction to Spark** – Understanding Spark fundamentals.
* 🔹 **RDD (Resilient Distributed Dataset)** – Core data structure for distributed computing.
* 🏗️ **Spark Architecture** – How Spark components interact.
* ⚙️ **Spark Context** – Entry point for Spark functionality.
* 🔄 **Transformations** – Operations like `map()`, `filter()`, `flatMap()` that define new RDDs.
* 🎯 **Actions** – Operations like `collect()`, `count()` that trigger execution.
* ⏳ **Lazy Evaluation** – Transformations are only computed when an action is called.
* 🗝️ **Key-Value RDD Operations** –

  * `groupByKey()`
  * `reduceByKey()`
  * `sortByKey()`
  * `keys()` / `values()`
* 🧩 **flatMap()** – Splitting elements into multiple outputs.
* 🧮 **Spark SQL** – Query structured data using SQL syntax.
* 📊 **DataFrame Object** – Optimized tabular data structure in Spark.
* 🔍 **DataFrame Functions** –

  * `explode()`
  * `split()`
  * `lower()`
* 🐼 **Pandas API on Spark** – Seamless integration with pandas-like operations.

  * Convert **Pandas DF → Spark DF**: `spark.createDataFrame(pandas_df)`
  * Convert **Spark DF → Pandas DF**: `spark_df.toPandas()`
* 🛠️ **User Defined Table Functions (UDTFs)** – Custom functions for complex transformations.
* 🖥️ **Spark UI** – Visualize jobs, stages, and tasks.
* 🤖 **Spark MLlib** – Machine learning capabilities:

  * Regression: Linear, Logistic
  * Classification: SVM, Naive Bayes, Decision Trees
  * Clustering: KMeans
  * Dimensionality Reduction: PCA, SVD
  * Recommendations: ALS
* 📚 **MLlib Library Imports** –

  ```python
  from pyspark.ml.regression import LinearRegression, DecisionTreeRegressor
  ```
* 🌊 **Spark Streaming** – Real-time data processing:

  ```python
  from pyspark.streaming import StreamingContext
  ```

---
