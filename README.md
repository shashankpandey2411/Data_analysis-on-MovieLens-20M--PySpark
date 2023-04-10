# Data_analysis-on-MovieLens-20M--PySpark

## This project will demonstrate how to get started using pySpark and the DataFrame API to perform some basic data analysis, including:

  -reading in data
  
  -performing aggregations and joins using the Spark SQL module 
  
  -calculating summary statistics
  
  We will use the MovieLens 20M Dataset on movie ratings to find out:

  What are the most popular movies?
  
  What are the top rated movies?
  
  Which movies are the most polarising?


## How to Run

 - Open Google colab notebook
  
  All the given steps are already followed in ipynb file, just need to upload the file in colab and run it.

- Install Java

  Download Java and install it in your computer

  Add Java to the path

  !apt-get update
  ### Download Java Virtual Machine (JVM)
  !apt-get install openjdk-8-jdk-headless -qq > /dev/null


- Setup Java

  Add "JAVA_HOME" variable to environment variables
  
  Copy the path and paste it in JAVA_HOME variable
  
  os.environ["JAVA_HOME"] = "/usr/lib/jvm/java-8-openjdk-amd64"

- Setup Hadoop

  Add ```"HADOOP_HOME"``` to environment variables

  In the git repo there is hadoop folder

  Copy the link to that folder

  Add it to HADOOP_HOME variable

- Setup Spark

  Add ```"SPARK_HOME"``` to environment variables

  In the git repo there is spark zip

  Unzip that 

  Copy the link to that folder

  Add it to ```SPARK_HOME``` variable
  
  ### Download Spark  
  !wget -q https://archive.apache.org/dist/spark/spark-3.2.1/spark-3.2.1-bin-hadoop3.2.tgz
  ### Unzip the file
  !tar xf spark-3.2.1-bin-hadoop3.2.tgz

- Setup Pyspark

  Setting up Pyspark variables

  Go to environment variables 
  
  os.environ["SPARK_HOME"] = '/content/spark-3.2.1-bin-hadoop3.2'

- Final Path setup

  Go to Path in environment variables and add

  ```%SPARK_HOME%\bin```

  ```%HADOOP_HOME%\bin``
