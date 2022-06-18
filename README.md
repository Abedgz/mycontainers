docker build -t flask_docker

####
docker run -d -p 5000:5000 flask_docker
####


##to add docker hub :

u should be have accound on hub docker.

first of all run command: docker login , from cmd 

docker tag flask_docker:1.2 abedgm/flask_docker:1.2


docker push abedgm/flask_docker:1.2


TEEST
