# DOCKER

cd/app
docker build -f Dockerfile-22 -t todo:22 .

docker scout quickview

docker run -p 3000:3000 --name  todo-app-22 todo:22