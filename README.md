# docker-test-app
My first Docker experience.

## Docker image:
https://hub.docker.com/repository/docker/aasineln/test_app

## Teriminal
docker build -t test_app
docker run -p5050:5050 -e "SERVICE_NAME=service1" test_app
check: curl http://127.0.0.1/hello/andrey
