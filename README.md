# jenkins
LEVANTAR JENKINS
Descargamos la imagen de Jenkins:
  sudo docker pull jenkins/jenkins:lts
 
Creamos la red:
  docker network create Jenkins

Creamos el archivo “docker-compose.yml”:

Levantamos el Jenkins:
  docker-compose up –d
 
