docker swarm init

docker stack deploy -c docker-compose.yml mystack

docker service ls

docker service ps mystack_web

docker service update --replicas=5 mystack_web

docker service scale mystack_web=5