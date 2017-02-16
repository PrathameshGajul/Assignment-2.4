Q1.Explain hadoop in layman's term
Ans:
Hadoop in Layman's term is based on two components:
1)Storage - HDFS
2)Processing - Mapreduce
              a)Pig
              b)Hive
 HDFS:
 -Using a HDFS storage solution can provide a number of benefits.
 -Firstly, compute and storage can be scaled independently rather than within the fixed capacity of a node.
 -There is also the option to provide faster data ingest and to view file contents directly in the cluster.
 -Both data and capacity can be shared between multiple Hadoop instances and an increased level of protection around the HDFS metadata can be provided.
 -In a standard Hadoop deployment, the namenode is a single point of failure, but can be manually replicated.
 -While HDFS provides features for automated data recovery and integrity checking, an HDFS storage solution can offload this work and reduce the need to maintain three copies of data across an instance.
 
 Mapreduce:
 -MapReduce is a framework using which we can write applications to process huge amounts of data, in parallel, on large clusters of commodity hardware in a reliable manner
-MapReduce is a processing technique and a program model for distributed computing based on java.
-The MapReduce algorithm contains two important tasks, namely Map and Reduce.
-Map takes a set of data and converts it into another set of data, where individual elements are broken down into tuples (key/value pairs)
-Secondly, reduce task, which takes the output from a map as an input and combines those data tuples into a smaller set of tuples.
-The major advantage of MapReduce is that it is easy to scale data processing over multiple computing nodes.

Pig & Hive:
-Hive Hadoop Component is used mainly by data analysts whereas Pig Hadoop Component is generally used by Researchers and Programmers.
-Hive Hadoop Component is used for completely structured Data whereas Pig Hadoop Component is used for semi structured data.
-Hive Hadoop Component operates on the server side of a cluster whereas Pig Hadoop Component operates on the client side of a cluster.



Q2.Explain the components of Hadoop framework
Ans:
The Hadoop framework consists of 4 core components –
1)Distributed File-System
  -Distributed File System allows data to be stored in an easily accessible format, across a large number of linked storage devices.
  -HDFS holds very large amount of data and provides easier access.
  -To store such huge data, the files are stored across multiple machines.
  -These files are stored in redundant manner to prevent the system from possible data losses in case of failure.
  -HDFS also makes applications available to parallel processing.
  
2)MapReduce
-MapReduce is named after the two basic operations
a)reading data from the database & putting it into a format suitable for analysis (map)
b)performing mathematical operations(reduce)

3)Hadoop Common
-Hadoop Common provides the tools (in Java) needed for the user’s computer systems(Windows,Unix etc) to read data stored under the Hadoop file system.

4)YARN
-YARN which manages resources of the systems storing the data and running the analysis.



Q3.Explain the reasons to learn Big data technologies.
Ans:
1)Big Data is now a priority for top organizations
-Big data professionals have a huge influence on company policies and marketing strategies.
2)Big Data is used everywhere nowadays.
3)Options for various job titles-Bigdata engineer,data analyst etc.
4)Develop new revenue streams
-With the ability to analyze and put good data information to good use we can easily identify new and unexploited streams of revenue generation.
5)Adoption rate of big data analytics is high
-Social media such as Facebook & twitter.
6)Increasing pay for Big data professionals
-Big data professionals are paid more than the other IT professionals.
