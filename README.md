# Atelier Server

## Description

The back end service built from scratch, this microservice was built to support the Atelier client. 


### ETL

The ETL process was automated using Mongoimport and MongoDB's aggregation pipeline to combine fivedependent datasets, totaling over 12 million records to save 5 days of processing time.


### Optimization

Performance bottlenecks were identified using K6, Loader.io, and New Relic.


### Scaling

By replicating the database and deploying servers on EC2 instances using NGINX for load balancing, the microservice was scaled to handle 1000 RPS with 0% error rate. All EC2 instances were t2.micro.



