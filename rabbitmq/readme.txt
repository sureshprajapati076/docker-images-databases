
docker container ls -a

docker container rm -f container-id


INSTALLING: 

docker pull rabbitmq:3-management



docker run -d -p 15672:15672 -p 5672:5672 --name rabbitMQService rabbitmq:3-management


http://localhost:15672/#/

User: guest
pass: guest