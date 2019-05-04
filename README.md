# bigdata-hadoop-spark-yearn-hbase-hive-playground
BigData Hadoop Playground

https://www.edureka.co/blog/install-hadoop-single-node-hadoop-cluster
https://neemaw.blogspot.com/2019/03/apache-open-source-configurations.html
https://drive.google.com/file/d/1bFm46gLYfwuLGJqxYdfI-kfzEZKV_Jeg/view




mkdir ~/hadoop-playground
cd ~/hadoop-playground
wget https://archive.apache.org/dist/hadoop/core/hadoop-2.7.3/hadoop-2.7.3.tar.gz
tar -xvf hadoop-2.7.3.tar.gz

set hadoop home
set java home

- set path 
sudo vim /etc/paths


- configure:

bin/hadoop namenode -format

- start 

./start-dfs.sh
./start-yarn.sh

http://localhost:50070
