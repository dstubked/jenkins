# Jenkins auto build for demoes
This builds a Jenkins docker image you can use for testing. It skips the setup process for you.
Please take note it comes with a default user name and password as you can see in the Dockerfile.
Not recommended for production!!!!

## Build command in Docker
docker build -t dstubked/jenkins:latest .

## Run the container
docker run -d --name jenkins-server -p 8080:8080 dstubked/jenkins:latest
