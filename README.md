# Project definition
today in a day of data. data needs a complex infrastructure to be processed. We have chosen the most useful tools for data engineers to develop their infrastructure simply on different machines using Ansible and Docker-compose.
you can customize it as a cookie-cutter project according to your company's requirements.

## Our stack
1. MongoDB
2. Apache Airflow
3. Apache Kafka
4. Postgresql
5. Redis
6. Cassandra
   
# How to Use it?
you can clone the project by `git clone` and inside a directory, you run `cookiecutter .`<br />
you will answer the questions we have asked and the project will be created.<br />
you can run the playbook with `sh run_ansible.sh` inside a project you created with a cookie-cutter.

## Services address
`localhost:8080`: Airflow WebServer<br />
`localhost:27017`: MongoDB<br />
`localhost:6379`: Redis<br />
`localhost:9092`: Kafka<br />
`localhost:9042`: Cassandra<br />
