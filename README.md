# build image
docker build . -t <image name>

# run container
docker run -dp 9090:8080 express-app:v0.0.1