# TRABALHO-DOCKER
Repositório do trabalho docker 


Seguir os seguintes passos:<br/>
1 - docker login<br/>
2 - docker build -t leofuzita/docker-bira:1.0 .<br/>
3 - docker push leofuzita/docker-bira:1.0<br/>
4 - docker pull leofuzita/docker-bira:1.0<br/>
5 - docker container run --name docker-bira -p -d leofuzita/docker-bira:1.0<br/>
6 - docker inspect CONTAINER ID<br/>
7 - usar o endereço que está em "IPAddress": "172.17.0.X"
