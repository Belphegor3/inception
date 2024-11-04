# inception

```bash
sudo docker stop $(docker ps -q)
sudo docker rm $(docker ps -aq)
sudo docker rmi -f $(docker images -q)
sudo docker system prune -af
sudo docker volume rm $(docker volume ls -q)
sudo docker network rm $(docker network ls -q) 2>/dev/null
```
