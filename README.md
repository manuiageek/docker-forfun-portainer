This repository serves as a reminder to set up portainer

## Create volume
docker volume create potainer_data

## access

https://localhost:9443

Beware if you wait too long, you need to reboot the docker to access it the first time :

docker compose down && docker compose up -d
