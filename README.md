# spring-boot-docker-template

Run SpringBoot application in a docker container

cd spring-boot-docker
docker build -t umeshlewa/spring-boot-docker .
docker run -p 8000:8080 umeshlewa/spring-boot-docker

--to run in background
docker run -d -p 8000:8080 umeshlewa/spring-boot-docker

docker push umeshlewa/spring-boot-docker

docker ps -a
docker images

docker stop "containerid"

--to delete image
docker rmi "imageid"

--to delete container
docker rm "containerid"
