docker build -t hello-saludo .
docker run -p 8080:8080 hello-saludo
curl http://localhost:8080/saludo