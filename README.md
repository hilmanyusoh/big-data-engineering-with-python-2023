# big-data-engineering-with-python-2023
Big Data Engineering with Python 2023 Course


### Overview
This project involves connecting the database with Cassandra and entering Quran data into the database in order to analyze the data.

-----
* **Tools**
    * Cassandra
    * Jupyter Lab

* **Installation**
    * Java 8
    * Python v2.7
    * cassandra
    * Python libraries:
        * pandas
        * cassandra
        * re
        * os
        * glob
        * numpy
        * csv
        * matplotlib
        * requests
        * fuzzywuzzy
        * collections
        * nltk

# Methodology
1. **Set up Cassandra**
    * Open Cassandra
        * Can open in terminal or cmd

    ![open cassandra](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-28%20at%2014.19.04.png)
                
    * Open cqlsh to use Cassandra

    ![Open cqlsh](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-28%20at%2014.19.54.png)

2. **Connect Cassandra with Python**
    * `pip install cassandra-driver` to use the cluster module

    ![Install Cassandra driver](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-28%20at%2023.57.03.png)


3. **Create Keyspace**

    ![Create Keyspace](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-28%20at%2023.57.03.png)


4. **Use Keyspace**

    ![Use keyspace](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-29%20at%2000.18.26.png)

5. **Create Table**

    ![Create Table arabic](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-29%20at%2000.22.33.png)

    ![Create Table tafseer](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-29%20at%2000.23.02.png)

6. **Extract Data from CSV**

    ![Extract data1](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-29%20at%2000.58.30.png)

    ![Extract data2](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-29%20at%2000.59.04.png)

7. **Check Table**

    ![Check Table arabic](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-29%20at%2001.10.00.png)

    ![Check Table tafseer](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-29%20at%2001.10.39.png)


8. **Code for Find the Answer**

    * Code to find English word
    
    ![code for english](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-29%20at%2001.28.39.png)

    * Code to find Arabic word 
    
    ![code for arabic](https://raw.githubusercontent.com/hilmanyusoh/big-data-engineering-with-python-2023/main/image/Screenshot%202567-03-29%20at%2001.29.41.png)

# Questions and Answers

1. **How many times does the phrase Allah appear in the Quran?**
   - Answer: The phrase Allah occurs 601 times in the Quran.
