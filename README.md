# PySpark

![logo](./img/spark.png)

Spark is a great language for performing exploratory data analysis at scale, building machine learning pipelines, and creating ETLs for a data platform. Spark is a must for anyone who is dealing with Big-Data. Using PySpark (which is a Python API for Spark) to process large amounts of data in a distributed fashion is a great way to manage large-scale data-heavy tasks and gain business insights while not sacrificing on developer efficiency. In a few words, PySpark is a fast and powerful framework to perform massive distributed processing over resilient sets of data.

<hr>

## Motivation

This repository contains several examples of PySpark functions and utilities that can be used to build complete ETL process of your data modeling. The posts are more towards people who are already familari with Python and a bit of data analytics knowledge (where I often skip the enviornment set-up). But You can always follow the [Installtation section](Installation), then you should be able follow the notebook with no big issues. PySpark allows us to use Data Scientists' favoriate [Jupyter Notebook](https://jupyter.org/) with many pre-built functions to help processing your data. The contents in this repo is an attempt to help you get up and running on PySpark in no time!

<hr>

## Table of contents
* [Installation](#Installation)
* [PySpark Notebooks](#PySpark)
* [Contact](#Contact)
* [Reference](#Reference)

<hr>

## Installation

Downloading PySpark on your local machine could be a little bit tricky at first, but 

First things First, make sure you have Jupyter notebook installed

1. Install Jupyter notebook

```
pip install jupyter notebook
```

2. Install PySpark
Make sure you have Java 8 or higher installed on your computer. 
But most likely Java 10 would through an error. The recommended solution was to install Java 8 (Spark 2.2.1 was having problems with Java 9 and beyond)

Of course, you will also need Python (I recommend > Python 3.5 from Anaconda).
Now visit the [Spark downloads page](http://spark.apache.org/downloads.html). Select the latest Spark release, a prebuilt package for Hadoop, and download it directly.


3. Set the environment variables:

```
SPARK_HOME = D:\Spark\spark-2.3.0-bin-hadoop2.7
PATH += D:\Spark\spark-2.3.0-bin-hadoop2.7\bin
```

4. For Windows users,
- Download winutils.exe from here: https://github.com/steveloughran/winutils
- Choose the same version as the package type you choose for the Spark .tgz file you chose in section 2 “Spark: Download and Install” (in my case: hadoop-2.7.1)
- You need to navigate inside the hadoop-X.X.X folder, and inside the bin folder you will find winutils.exe
- If you chose the same version as me (hadoop-2.7.1) here is the direct link: https://github.com/steveloughran/winutils/blob/master/hadoop-2.7.1/bin/winutils.exe
- Move the winutils.exe file to the bin folder inside SPARK_HOME (i.e. C:\Spark\spark-2.3.0-bin-hadoop2.7\bin)
- Set the folowing environment variable to be the same as SPARK_HOME:
HADOOP_HOME = D:\Spark\spark-2.3.0-bin-hadoop2.7


5. Restart (our just source) and Run pyspark command your terminal and launch PySpark:
```
$ pyspark
```

For video instruction of installtion on Windows/Mac/Ubuntu Machine, please refer to each of the YouTube links below
- Windows [Link](https://medium.com/@GalarnykMichael/install-spark-on-windows-pyspark-4498a5d8d66c)
- Max [Link](https://medium.com/@GalarnykMichael/install-spark-on-mac-pyspark-453f395f240b)
- Ubuntu [Link](https://medium.com/@GalarnykMichael/install-spark-on-ubuntu-pyspark-231c45677de0)

Or More Blogs on installations steps
- https://towardsdatascience.com/how-to-get-started-with-pyspark-1adc142456ec
- https://medium.com/big-data-engineering/how-to-install-apache-spark-2-x-in-your-pc-e2047246ffc3


<hr>

## PySpark

These examples display unique functionality available in PySpark. They cover a broad range of topics with different method that user can utilize inside PySpark.














## Contact
Created by [@hyunjoonbok](https://www.linkedin.com/in/hyunjoonbok/) - feel free to contact me!


## To-Do 
- Ultimate PySpark Cheat Sheet [Blog](https://towardsdatascience.com/ultimate-pyspark-cheat-sheet-7d3938d13421)
- Use Apache Arrow to Assist PySpark in Data Processing [Medium](https://medium.com/datadriveninvestor/use-apache-arrow-to-assist-pyspark-in-data-processing-6c1cce134306)


### Reference 
- Victor Romain's [Medium](https://towardsdatascience.com/@rromanss23?source=post_page-----485fb3c94e5e----------------------)
- Official PySpark Documentation [Link](https://spark.apache.org/docs/latest/api/python/index.html)
