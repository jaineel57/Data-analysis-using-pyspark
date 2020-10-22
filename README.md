# Data-analysis-using-pyspark
Introduction:
Spark is a unified analytics engine for large-scale data processing. It provides high-level APIs in Scala, Java, Python, and R, and an optimized engine that supports general computation graphs for data analysis. It also supports a rich set of higher-level tools including Spark SQL for SQL and Data Frames, MLlib for machine learning, GraphX for graph processing, and Structured Streaming for stream processing.
Apache Spark is a fast and general-purpose cluster computing system. Designed for large-scale data processing, it run programs up to 100x faster than Hadoop MapReduce in memory, or 10x faster on disk. Spark can run on Hadoop, Mesos, standalone, or in the cloud. It can access diverse data sources including HDFS, Cassandra, HBase, and S3. Spark has an advanced DAG execution engine that supports acyclic data flow and in-memory computing. It provides high-level APIs in Java, Scala, Python and R, and an optimized engine that supports general execution graphs.
Apache Spark is written in Scala programming language. To support Python with Spark, Apache Spark community released a tool, PySpark. Using PySpark, you can work with RDDs in Python programming language also. It is because of a library called Py4j that they are able to achieve this. This is an introductory tutorial, which covers the basics of Data-Driven Documents and explains how to deal with its various components and sub-components.
Objective:
The aim of this project is to perform data analysis on the dataset of stock market with the help pf apache spark. The program will be written in the python language, so the tool used in the project will be PySpark.
For the analysis purpose I have decided to use two different datasets for the project and with the help of PySpark I will be performing data analysis on each of the datasets.
Project Information:
Data analysis was performed on two datasets named:
1 Walmart Stock data.
2 Apple Stock data.
Initially in the start of the project the main thing to be done is importing the PySpark libraries, then with the help of PySpark libraries we will be reading the dataset and then performing the analysis on the dataset as per the requirements.
The dataset first I will be using is Walmart stock data and I will be using jupyter notebook for the data analysis using PySpark. The procedure followed by me is listed down below:
The first step done by me is importing PySpark libraries find spark and SparkSession from PySpark.sql.
The second step done by me is defining an object named spark with respect to the class imported from the PySpark.
The third step done will be reading the dataset using the object spark defined in the earlier step.
The next step onwards the data analysis part will be initiating and various different methods will be called and data will be retrieved from the dataset and will be shown in the form of the table in the output.
The Walmart dataset has 4 features named as Date, Open (The price at which stock price opened), Close (The price at which stock price closed), High, Low, Volume and Adj close.
With respect to the features we have the row containing the data and it can be checked in detail from the csv file provided along with the report.
By using PySpark.sql the dataset will be treated as SQL table and while writing the code we will be using various SQL Queries to retrieve data from the dataset.
The various PySpark.sql functions used are format_number, mean, min, max, corr, dayofmonth, hour, dayofyear, month, year, weekofyear, date_format for the Walmart stock data.
By using the PySpark.sql functions data analysis was done in detailed manner and the by implementing each function in the code will result out the required output.
The dataset next I will be using is apple stock dataset and I will be using jupyter notebook for the data analysis using jupyter notebook. The procedure followed is listed down below:
The first step done by me is importing PySpark libraries find spark and SparkSession from PySpark.sql.
The second step done by me is defining an object named spark with respect to the class imported from the PySpark.
The third step done will be reading the dataset using the object spark defined in the earlier step.
The next step onwards the data analysis part will be initiating and various different methods will be called and data will be retrieved from the dataset and will be shown in the form of the table in the output.
The apple dataset has 4 features named as Date, Open (The price at which stock price opened), Close (The price at which stock price closed), High, Low, Volume and Adj close. The dataset is similar to Walmart dataset so by scanning upon the output of the both the analysis the difference can be spotted out.
The analysis done on the apple dataset will be done using different conditions and the output will be shown for different conditions and the output can be viewed in the jupyter notebook in the form of table.
Similarly, using the PySpark.sql function the SQL Queries.
Experimental Environment:
Operating System – MacOS.
Software – Jupyter Notebook.
Language – python.
Libraries – findspark, pysaprk, numpy.
