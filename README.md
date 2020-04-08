# jenkins auto build for demoes

# Build command in Docker
docker build -t dstubked/jenkins:latest .

# Run the container
docker run -d --name jenkins-server -p 8080:8080 dstubked/jenkins:latest
