# Data_analysis-on-MovieLens-20M--PySpark

   The Movielens 20M dataset is a large-scale dataset containing user ratings and metadata for movies. In this project, we performed data analysis on the Movielens 20M    dataset using PySpark, a powerful big data processing framework.
   
   The analysis is performed using PySpark's distributed processing capabilities to efficiently handle large datasets. The study begins with data preprocessing, which    involves cleaning, filtering, and transforming the data into a format suitable for analysis.Exploratory data analysis techniques are then used to gain insights into    the dataset, such as identifying the most popular movies and genres, finding the most active users, and examining the distribution of ratings.

   ### Problem statement:
   The MovieLens 20M dataset contains movie ratings data from 20 million 
   users. The dataset is too large to be processed on a single machine using traditional data analysis tools. 
   Therefore, the goal of this project is to perform data analysis on the MovieLens 20M dataset using 
   PySpark, a distributed computing framework for big data processing


   ### This project will demonstrate how to get started using pySpark and the DataFrame API to perform some basic data analysis, including:

  - reading in data

  - performing Exploratory data analysis on the dataset
  
  - performing aggregations and joins using the Spark SQL module 
  
  - calculating summary statistics

   ### Objective of the project: 
   In this project, we are going to analyse using the movielens dataset using a PySpark and answer a few questions like the ones given below
   
   - How many number of Movies are there for each rating?
   - What are top 10 most rated movies?
   - How many users have rated each movie?
   - What is the Total Rating for each movie?
   - What is the Average Rating for each movie?
   - How many movies are there for each genre?
   - How many movies have been rated each year?   
   - Which were the least rated movies in the year of 2005? 
   - What are the genres of the top 5 rated movies? 
   - Which are the top rated by the users Sci-fi movies?
   - Which are the Worst Comedy movies rated by the users in the year 2012?
   - Find the number of users who watched the movie "Jumanji".
   - Find the names of the movies that users described as "boring".
   - Find the number of users who have described a movie as "Bollywood" and they have rated it with a score > 3.
   - Find the tags for each movie and the name of the movie before the year 2015 .
   - Find the movies with the most ratings for each movie category.
   - Find the total number of users watching the same movie, on the same day and time .
   - Find the number of movies, for each category, that users rated as "funny" and with a rating > 3.5


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
