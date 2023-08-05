keycloak 
how to run using docker-compose:

first create thre foldrs keycloak/data , keycloak/themes, and keycloak/conf

second give permitions : sudo chown -Rv user:user keycloak_path

sudo chown -Rv halmogbl:halmogbl /home/halmogbl/keycloak-21-1-1/keycloak

third run docker compose:
docker-compose down && docker-compose build --no-cache && docker-compose up -d 

docker-compose down && docker-compose build --no-cache && docker-compose up -d && docker-compose logs -f 

