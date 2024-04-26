This is an accompaying demo project for a "Docker in 1 hour" crash course on YouTube: https://www.youtube.com/@TechWorldwithNana

Build Inage
docker build -t node-app:1.0 .

Run Container
docker run -d -p 9000:3000 node-app:1.0
docker ps


on Browser localhost:9000
docker logs 78889c99a63d

docker stop 78889c99a63d 

