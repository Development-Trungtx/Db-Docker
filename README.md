Use docker, dockerfile & docker-compose build some demo database server in container on localhost, VMs, cloud.

1 - SSH on Server installed Docker & docker-compose

2 - Clone code

3 - cd path/to/database_folder

4 - Run container:

docker-compose up -d

5 - Down container

docker-compose down

** Note: If RabbitMQ:

Access Container interative run command:

rabbitmq-plugins enable rabbitmq_management

After:  
docker-compose down  
docker-compose up -d