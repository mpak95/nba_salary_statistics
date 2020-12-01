# NBA Salary Statistics
Repository utilizing py_ball (python library) and containers (hosting Apache Airflow, PostgreSQL database) to extract and calculate NBA team salary statistics.

##Introduction
This repository is mostly for learning purposes to teach myself how to:
- Use the py_ball python library to retrieve NBA data
- Understand and use Apache Airflow
- Transition from MySQL syntax to PostgreSQL syntax
- Create and manage Docker Containers 
- Utilize Github for documentation/demonstration

This repository will demonstrate the ability to automatically pull in NBA Team Salary data using the py_ball library, calculate the breakdown of each players salary in relation to the total team salary, and store that data in a PostgreSQL database.

The workflow management will be handled by Apache Airflow, and the data will be stored using a PostgreSQL database. Both applications will be stored in its own Docker Container.

##Goals
1. Create all functions to pull in NBA data and manage them in dataframes.
2. Create all functions to load dataframes into PostgreSQL database.
3. Setup Docker Containers for Apache Airflow and PostgreSQL database.
4. Create DAG to run all ETL processes to extract NBA data, modify them to suit my needs, and load them into PostgreSQL database.

##Roadmap
The initial goal is to simply learn the main functionalities of py_ball, Apache Airflow, PostgreSQL, and Docker.