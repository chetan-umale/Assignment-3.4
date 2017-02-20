Q1. Explain the importance of Namenode in Hadoop cluster.

answer:

1.NameNode is the centerpiece of  HDFS.
2.NameNode is also known as the Master
3.NameNode only stores the metadata of HDFS – the directory tree of all files in the file system, and tracks the files across the cluster.
4.NameNode does not store the actual data or the dataset. The data itself is actually stored in the DataNodes.
5.NameNode knows the list of the blocks and its location for any given file in HDFS. With this information NameNode knows how to construct the file from blocks.
6.NameNode is so critical to HDFS and when the NameNode is down, HDFS/Hadoop cluster is inaccessible and considered down.
7.NameNode is a single point of failure in Hadoop cluster.
8.NameNode is usually configured with a lot of memory (RAM). Because the block locations are help in main memory.


Q2-2. Practice the beginners commands for HDFS from the below link
https://acadgild.com/blog/hdfs-commands-for-beginners/
Share the screenshot of the commands used.


