# Commands

docker build -t ms-1 .
docker run --rm  -p 8000:8000 --name ms-1-c ms-1

docker tag ms-1 bchaparro4/devopssre-ms-1
docker push bchaparro4/devopssre-ms-1