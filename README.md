# bigdata-hadoop-spark-yearn-hbase-hive-playground
BigData Hadoop Playground

Install and Configuration:
https://www.edureka.co/blog/install-hadoop-single-node-hadoop-cluster
https://neemaw.blogspot.com/2019/03/apache-open-source-configurations.html
https://drive.google.com/file/d/1bFm46gLYfwuLGJqxYdfI-kfzEZKV_Jeg/view

Hello World:
https://examples.javacodegeeks.com/enterprise-java/apache-hadoop/hadoop-hello-world-example/


###############################################################################################


mkdir ~/hadoop-playground
cd ~/hadoop-playground
wget https://archive.apache.org/dist/hadoop/core/hadoop-2.7.3/hadoop-2.7.3.tar.gz
tar -xvf hadoop-2.7.3.tar.gz

#MacOS
set hadoop home
set java home

- set path 
sudo vim /etc/paths

#Linux



- configure:

bin/hadoop namenode -format

- start 

./start-dfs.sh
./start-yarn.sh

http://localhost:50070



cd $HADOOP_HOME
hdfs dfs -mkdir -p input
hdfs dfs -put input.txt input
hadoop jar share/hadoop/mapreduce/hadoop-mapreduce-examples-2.9.2.jar wordcount input output
hdfs dfs -ls output
hdfs dfs -cat output/part-r-00000












