# Notes
This is a reproduction project of the master thesis "Applying API Categories to the Abstractions Using APIs" (2021) written by Katharina Gorjatschev as part of the MSR course 2021/22 at UniKo, CS department, SoftLang Team.

# Team Name: India
* Sriram Aralappa (219203195)
* Manojkumar Krishnakumar (220200906) 

# Baseline Study: 

### Aspect of the reproduction project
We are collecting java repositories from Github and collecting dependencies which are eligible based on conditions given in the thesis paper for further process.

### Input data:
Using Github API we are collecting all repositories and then parsing these repositories files(CSV)  to find dependencies in Python.

### Output data:
 comma seperated (CSV) files which contain all dependencies of repositories.
 
# Finding of Replication:
 
### Process delta: 
We had only a difference in execution time. It took a lot of time to execute(only collecting repositories part in Java). We believe this is because of the limited computational resources we have. 

###  Output delta: 
We were able to collect 3757 repositories. Dues to this we got different dependencies when compared to what we have in thesis.

# Implementation of Replication: 

### Software
* Java 11 (Maven project)
* Python 3.9( pyspark==3.1.2)

### Data
We were able to produce csv files which contain Java repositories name and eligible dependencies file.

# Notes
You need to create a personal access token in your GitHub account and then replace the `USERNAME_AND_TOKEN` in `RepositoriesPicker.java` with your username and token.
