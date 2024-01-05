# cloud computing 

## Content

### dockerfile
This project involved creating a container-based website to deploy PHP-based webpages using Nginx and PHP in one container. The main tasks included writing a Dockerfile to containerize these applications, allowing colleagues to upload and test PHP websites in the container without issues. Key technical requirements included using Ubuntu 18.04 as the base image, installing Nginx and PHP-FPM, configuring Nginx to support PHP-FPM, and ensuring accessibility from outside by exposing and publishing port 80. 

### docker-compose
This project involved writing a docker-compose.yml file to orchestrate five containers: Nginx, PHP-FPM, phpMyAdmin, Redis, and MariaDB. The task required utilizing Git to download setting files and test web pages, customizing Docker containers, and defining a network for container communication. Key aspects included setting up MariaDB with specific environment variables, ensuring PHP-FPM could communicate with Redis and MariaDB, and configuring Nginx and phpMyAdmin containers. The goal was to facilitate the testing of PHP websites in a microservices architecture using Docker.

### RDD Programming
The project involved analyzing Shakespeare's works using Spark RDD programming to count verb occurrences. The process included text processing for punctuation removal and case conversion, and verb matching from a provided list. The task focused on merging different verb forms for collective occurrence counting and identifying the top 10 most frequently used verbs. This required handling data in RDDs and applying transformation and action operations in Spark, using Python in a Jupyter Notebook environment.

### data-analytic-application
This project involves analyzing health data for around 500 of the most popular cities in the U.S., focusing on chronic diseases, health outcomes, and clinical preventive services. The aim is to assist health departments in better planning public health programs by understanding the distribution of health-related issues. The project utilizes cloud computing for big data queries, ensuring cost-effectiveness and security. Technologies used include Matplotlib for data visualization, HDFS for data storage, Jupyter Notebook for data analysis and visualization, and Spark SQL for backend processing. The cloud infrastructure is based on Google Cloud Platform, with an emphasis on affordability and simplicity in deployment.