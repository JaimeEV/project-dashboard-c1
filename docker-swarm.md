docker swarm init
docker node ls
docker swarm leave

docker-compose up --scale api=3

docker service ps
docker service ps pinger
docker service create --name pinger alpine ping www.google.com
docker service scale pinger=5


db.platzi-dashboard.com
api.platzi-dashboard.com
platzi-dashboard.com
celery.platzi-dashboard.com