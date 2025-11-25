<p align="center">
  <img src="/assets/5.png" alt="Big Data Banner" width="100%">
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,java,mysql,git&theme=dark" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/hadoop/hadoop-original.svg" width="48"/>
  <img src="https://skillicons.dev/icons?i=ubuntu,vim&theme=dark" />
</p>

---

<h1 align="center">⊹₊⟡⋆ Big Data Technologies ⋆⟡₊⊹</h1>

A comprehensive collection of my **Big Data learning journey**, consisting of:
- **Individual assignment** on Big Data concepts and applications  
- **Hands-on lab reports** covering Linux commands, HDFS, Hadoop MapReduce, HBase, Apache Pig, and Apache Impala  

This repository highlights my practical understanding of **distributed systems, large-scale processing, Hadoop ecosystem tools, and query frameworks**.

---

## ⊹₊⟡⋆ Repository Overview

### **1. Individual Assignment**
A written analysis on:
- Big Data characteristics  
- Hadoop ecosystem overview  
- Distributed storage concepts  
- MapReduce workflow  
- Industry use cases  

📄 *File:* [individual assignment](assignment/IndividualAssignment.pdf)  

---

### **2. Lab Reports — Big Data Hands-On**
A collection of detailed lab practices covering:

#### ✔ Linux + VirtualBox + Cloudera setup  
- Installing VirtualBox, importing Cloudera VM  
- Navigating Linux commands (`ls`, `cat`, `mkdir`, etc.)  

#### ✔ HDFS & MapReduce  
- Creating folders in HDFS, using `hdfs dfs` commands  
- Uploading files into HDFS  
- Implementing Hadoop **WordCount**  
- Interpreting Yarn & MapReduce job logs  

#### ✔ HBase  
- Starting HBase services  
- Creating tables, inserting rows, versioning, timestamps  
- Scanning tables and altering schema  

#### ✔ Apache Pig  
- Running Pig in Local and MapReduce modes  
- Loading relations, filtering data, grouping, aggregations  
- Storing results in HDFS and local  

#### ✔ Apache Impala  
- Starting impala-shell  
- Creating databases and tables  
- Inserting records  
- Running queries  
- Altering and dropping tables  

---

## ⊹₊⟡⋆ Technologies Used

<p align="left">
  <img src="https://skillicons.dev/icons?i=linux&theme=dark" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/hadoop/hadoop-original.svg" width="48"/>
  <img src="https://skillicons.dev/icons?i=mysql&theme=dark" />
  <img src="https://skillicons.dev/icons?i=java&theme=dark" />
  <img src="https://skillicons.dev/icons?i=git&theme=dark" />
</p>

- **Linux CLI (Ubuntu on Cloudera VM)**
- **HDFS**, **MapReduce**
- **HBase**, **Apache Pig**, **Apache Impala**
- **VirtualBox**, **Cloudera QuickStart VM**

---

## ⊹₊⟡⋆ Commands Practiced

### **Linux Basics**
```sh
ls
cat
mkdir
pwd
sudo jps
```

### **HDFS Commands**
```sh
hdfs dfs -ls /
hdfs dfs -mkdir /inputfolder
hdfs dfs -put file.txt /inputfolder/
hdfs dfs -cat /inputfolder/file.txt
```

### **Hadoop MapReduce**
```sh
hadoop jar WordCount.jar WordCount /inputfolder/file.txt /outputfolder
```
### **HBase**
```sh
hbase shell
create 't1','cf'
put 't1','r1','cf:c1','v1'
scan 't1'
```

### **Pig**
```sh
pig -x local
grunt> LOAD ... USING PigStorage(',')
grunt> FILTER employee BY sales > 400
grunt> DUMP employee
```

###  **Impala**
```sql
CREATE DATABASE retaildb;
USE retaildb;
CREATE TABLE retailers (...);
INSERT INTO retailers VALUES (...);
SELECT * FROM retailers;
```

## ⊹₊⟡⋆ Skills Gained
- Understanding of Hadoop Distributed File System (HDFS)
- Running MapReduce jobs and analyzing logs
- Creating and managing HBase NoSQL tables
- Writing Pig Latin for ETL workflows
- Querying large datasets using Apache Impala
- Navigating Linux environments using terminal
- Working with virtualized Big Data environments (Cloudera)
