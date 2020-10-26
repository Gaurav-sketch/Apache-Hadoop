# Apache-Hadoop
A documentation on understanding of Big data and Hadoop ecosystem.

### Introduction to Big Data :
Big Data is also data but with a huge size. Big Data is a term used to describe a collection of data that is huge in volume and yet growing exponentially with time. In short such data is so large and complex that none of the traditional data management tools are able to store it or process it efficiently.

### Hadoop:
Hadoop is an open-source software framework for storing data and running applications on clusters of commodity hardware. It provides massive storage for any kind of data, 
enormous processing power and the ability to handle virtually limitless concurrent tasks or jobs.

### Setup:
First installed Virtual Machine and open Cloudera into that.Cloudera is built on Ubuntu.So now 
if you want to work from windows install Putty(provide IP address of VM) and connect through SSH(Secure shell) to the virtual Linux Environment.Now , using Putty you can work on your virtual local machine.
Now you can use the Linux commmands to work in linux environment , and if you want to work in Hadoop environment you need to learn some of the Hadoop Commands.There are functions like moving , copying ,creating , listing , local to Hadoop , Hadoop to local etc.
We know that the same is available for linux too but bit of difference wrt syntax.

### Term meaning:
Stack - A storage device that handles data so that the next item to be retrieved is the item most recently stored (LIFO).
Stack - An orderly pile

### Why Big Data ?
1)Any login , will give you recommendation based on the historical data 
2)Huge Volume of historical data ,based on this recommendation 
3)Banking system - Customer is capable or not 
4)Data plays vital role 
5)Self driving car 
6)Weather report 
7)Whatever decision we make in life based on churning the data 
8)Huge volume of transactional data per second 
9)Lot of data 
10)Big Data - lot of Data - Big Data eco system - ETL-Pipeline -where extract huge amount of data - process it -
apply ML /DL model , Tableau ,deploy model.
11)Each and every organisation has the demand for this.

### Hadoop Ecosystem :
- Build ecosystem which support eco system for longer period to generate revenue 
- Learn each and every technolgical stack /architectureof this entire big data ecosystem , able to design own Big data solution ,
,deploy into Azure , oracle , Alibaba ,Pivotal cloud etc.Docker and Kubernetes etc production grade system.There are different stack important in BIG Data 
like Hadoop , Map reduce , Hive , Spark streaming ,Spark ML,Impala, PIG ,KFAKA ,Spark SQL.
- At each transaction there will be data generated online shopping , movie ticket transaction etc 
- This is required to make any financial decision
- Recommendation of any product or movie 
- Big data stack - Hadop , scoop , Spark graphics
- architecture overview of cloud ,SQL,No SQL , Kaafka , Cassandra ,Apache Hbase
- For interview , aware of the both technological and architectural overview 
- Implementation is there to give you confidence 
----------------------------------------------------------------------------------------------------------------------
### Hadoop System setup :
- Setup system , Hadoop , problem with exisitng , Flumes ,kapka 
- We need envirmonemt in local system , on cloud also we can do create environment like EC2(where configure multinode cluster) , Elastic Mapreduce Multinode cluster 
- Run each and every code with help pf distributed computation 
- Setup local infrastructure into our virtual environment 
- How configure Cloudera environement provides 

1)Cloudera distributed system 
2)Cloudera Virtual Environment
Cloudera, Inc. is a US-based software company that provides a software platform for data engineering, 
data warehousing, machine learning and analytics that runs in the cloud or on premises. 
3)VMware develops virtualization software. Virtualization software creates an abstraction layer over 
computer hardware that allows the hardware elements of a single computer— processors, memory, storage, and more
4)Virtual Machine Software - VMware
5)you need a Virtual Machine when you want to test an Operating System in aspects of aesthetics, usability and functionality.
You need a VM when you think a specific OS might cause trouble to your work computer.
6)Using different operating system is the advantage of VM 
7)Cloud computing is the on-demand availability of computer system resources, especially data storage and computing power, without direct active management by the user. 
The term is generally used to describe data centers available to many users over the Internet.

### Practical approach and components of ecosystem:
Start with Practical Now:
- Through VMware open Cloudera open virtulisation software
- HUE is Hadoop User Experience -Cloudera has created - whatever query you can do , CLI or HUE - browse each and every dataset in hadoop(Entirely on Java)
- NameNode:Stores the Meta information of the file you dunp in Hadoop , location and this is a process which contains the 
information of the each and every file in Hadoop
- Different-2 file with different types services of Hadoop ecosystem
- all files log information 

Hbase 
- NoSQL database (Widely used)
- Some special feature
Impala 
- like Hive 
- but has some difference 

Spark 
- In memory data computation engine

Solar
-Query processing

Oozie 
-Scheduling a task 
-Map reduce job scheduling 
-Hive task scheduling 
-shell script 
-Pig script 
-HQl(HiveQL)

Cloudera Manager 
- UI interface 
-Monitor each services 
- Start and stop each configuration that you have in hadoop environment

Cludera using Ubuntu OS 16.X built on that
-on real time env , actual distribution on Cloud env where all distribution is there,so you have to login through third party 
admin will provide the IP address ,UID and PW. through SSH
- Commands used - ifconfig(gives config), jps(Services up and running) ,hadoop -fs -ls/

Through this will be able to login in cloudera environment.
- For windows use - Putty tool you can do SSH .
- Linux you can do directly.
- Its a terminal hitting your virtual box/server 
- Work in cloudera env using Putty

### Linux Commands:
As a Hadoop developer , Big Data Engineer :-
Basics of Linux Commands:
ls:each file in the directory home
pwd : present working directory
ls -l : This gives all the files in the vertical list
clear : This is to clear my window 
man ls: What the linux command does , gives all details 
mkdir : Create directory 
:wq : to save file 
vi text.txt :create file
cat : This gives what data is present in the file 
rm : this is to remove the file 
cd .. : this is to go back to your previous directory 
cd ../../ :Absolute home directory of linux 
/ :This is the absolute path 
cd home/ : To home directory
cp /home/cloudera/test1/test1.txt /home/cloudera/test2 :To copy file

### Data Enigneer (key commands):
Data Engineer should know the below things:
-This is somthing within Virtual Machine.
If you wan to check the permissions to a file do ls -l
symbol d means -create directory 
permission how to give to any file 
chmode 777 test1 -change the permission 
chmod -R 777 test1 : to all the files in single shot read,write and execute 
delete -RF something in directory forcefully delete it 

### Remember some Hadoop Commands:
As a Data Engineer you should know all these commands :
Hadoop command :
Cloudera :
-Base environment 
-Hadoop Environment 
you have to execute few hadoop command to get he filed in hdfc hadoop env.
- This found six file in the environment of Hadoop present 
- The command used is hadoop fs -ls /
- hadoop fs -mkdir /test5 
- hdfs dfs -ls / to get all the files present in the HADOOP environment 
- hadoop fs or hdfs dfs in front of Linux command to get the things done for hadoop environment
- Copy the file from the local to directory using Hadoop Command 
- hadoop fs -cat /Auto
- List all the file in hadoop fs -ls /
- hadoop fs -moveFromLocal check.txt /test6 this will move file permanently to test6
- -put : This is to put the file from local to Hadoop 
- -get : This is to get the file from Hadoop to local
- -cp test6/check.txt /test8 this is to copy file within hadoop environment
- hadoop fs -mv /test6/check.txt /test9
- hadoop fs -copyToLocal /test9/check.txt
- hdfs dfs -df / , this gives you the total space of hdfs , used ,available etc 
- hdfs dfs -du / , what all files present and their utilization

*As a Big Data Engineer you should know the Linux and Hadoop commands : *
Hadoop in Linux :
Hadoop fs -ls / :This is how you go into the Hadoop
Hadoop fs -ls -R / :This gives each and every file in Hadoop machine.File inside a file ,root directory path
hadoop fs -ls -h / : File format and file size , this could be zero if no file inside directory 
hadoop fs -ls -d /: directory each and every plane file 
--You cannot create a dataset with same name or kinda duplicate in the same Hadoop environment/Folder
--No override
--The permission grant has to be given to the file in hadoop using chmode to retrieve/get the file from hadoop to local machine.


How to solve Big Data challenges :
Data that is having high volume , high variety and high velocity is called a BigData
1st approach Scale up : Req 10GB Disk size and 2GBRAM , accmodate all data, if more generated data then configure new system with 30GB of HD and 5GB Ram ,migrate all from 1st to 2nd sys, there will be latency 
100 GB HD , moving to new system.
2nd Approach Scale out : Adding of new system to existing system , no migration etc needed here , data transfer headache will go off.
So scale out approach is a better and good approach , entire HDFS is designed on this.
HDFS : Hadoop Distributed File system is designed.

### Scale In and Scale Out Approach:
There are problems with Scale out approach also :
- Client make request to Database(This is only stores the data) ,and this passed to the server for processing (Ram , Hardisk and CPU) , then replied back to the Client
- Here any added system failure could lead to failure of entire system , so this is also not good 
- New arrangement is still needed to overcome this kind of challenges so lets look at that 
- Mutliple copy of file , and processing within system 
- A system capable to keep all the information with itself , in particular Meta data , and does processing etc on time
- Google published GFS ->dUCK KATTIN HAS developed -HDFS - This is a file system (not database)where data is in the system and is processed there only , helps in distributed computation , whatever computatio going on other system would be managed by it and assign job.
- Duck kttins child toy elephant named Hadoop , from there this name came.

### Hadoop Design and History:
About Hadoop:
GFS -Google File system 
HDFS - Hadoop file system (tries to store data/information), this is open source library , anyone can distribute it , hdfs supports each programming lang, but hadoop itself built on Java
, this supports processing of large dataset in distrubuted computation environment , hadoop is reliable and saclable platform.Not going to loose any data , multiple copy of data .
Any time if more hardware for computation in distributed , less time to add new hardware , Hadoop can run number of applications, bunch of system in sycn -cluster,service named as nam node.
-Map reduce: this is a computation framework , responsible for execut of data availbale in distrubuted , computation in distri system
-Hardware Failure : Configurable copy of file of same thing , replica of three , any info in Hadoop , replica in different , no data loss
- HDFS - storage unit ,file system not a processing unit at all , not database
- Map reduce - 	so processing unit on top of hdfs called map reduce 

### Components of Hadoop :
Components of Hadoop1.x :
1)Name node - This contains meta information about each and every file present in Hadoop Environment.While processing check here whether file is there or not ,not available store data then
This first poc and most important concept MAster Slave architecture.This always store Minfornation,FS image(File system Image) , in memory maping of all the files
2)Secondary name node ->Services that help name node to create a Backup and new.This helps to create a FS image , merging the new metainfo with previous  
3)Job Tracker -> control execution of Map reduce , assigning process to each node , based on job exec in each node(Master) , overall system 
4)Task Tracker ->Individual node ()within Mapreduce , check each job and notify to Job tracker
5)Data Node -> final end here 

### More to HDFS design :
HDFS Design : 
1) For large file system , and can process it in distributed computation environment
2) Streaming dataset , process data in streaming env as well
3) It supports commodity hardware 
4) Cluster computation : 
5) Blocks : Store data in form of small chunks or blocks MB or KB 
6) Fault Tolerance : Not loose any data 
7) Data is available in continuous form in HDFS , not random so easy access to data 

### How the Processing happens ?
HDFS X1.0
NameNode :
Client ->Namenode->meta-FSImage ->File available or not 
Namenode ask job tracker ->in which node dataset is available -multiple -ask each traker to find the file TT(Task Tracker)
Data Node (system) this will be having the computation power RAM , CPU etc
Master : (Name Node and JobTracker)
Slave : (Task tracker and Data base node)  


### The End


