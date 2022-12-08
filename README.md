# Welcome to Cassandra start project!

The objective of this project is to practice knowledge in the Cassandra database, applying the basic concepts of data modeling within the NoSQL paradigm.


## Files and descriptions
|           File                |        Description          |
|-------------------------------|-----------------------------|
|`Cassandra-Start-Project.ipynb`|Main file to run the ETL in Cassandra |

* All the instructions for running the ETL will be inside the main file.

# Dependencies
First of all we must make sure that two dependencies exist:
  1. Install Cassandra driver <br>
  `pip install cassandra-driver`
  2. An instance of cassandra available <br>
    For a test environment I recommend creating a local docker instance. <br>
    `docker run --name cassandra-name -p 9042:9042 -d cassandra:latest` 
