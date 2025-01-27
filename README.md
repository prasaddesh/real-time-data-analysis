# Real-time-data-analysis
End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka
We are going to use different technologies such as Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL.

Step 1:
Create a EC2 instance on AWS using a linux AMI

Step 2:
Use the command_kafka.txt file to setup the kafka cluster on the EC2 instance

Step 3:
From your local machine install any IDE ( jupyter notebook ) and run the python code to fetch the stock data from .csv file into S3

Step 4:
Once files are in S3  use crawler to catalog data in athena.
