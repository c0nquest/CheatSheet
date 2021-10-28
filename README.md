# CheatSheet
Linux DevOps Cheat sheet commands
Docker

Run with bash cmd
docker exec -it <container-name> bash
  
docker run --name <container-name> -p 8080:8080 -d <container-name> 
  
  
Delete all containers
docker rm $(docker ps -a -f status=exited -q)

Delete all images
docker rmi $(docker images -a -q)

