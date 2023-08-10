## Docker compose 

docker compose file to run posgresql pgAdmin on docker.

run this command
> docker compose up

and later run 
> docker ps
to see the containers running.

and then run 
> docker inspect <container_id>
to see the `ip address`.

with the `ip address` connect the pgAdmin server.