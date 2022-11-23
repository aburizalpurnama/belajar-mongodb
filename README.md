# belajar-mongodb
Go + MongoDB

## Run mongoDB from docker
    
    docker compose -f ./mongo/docker-compose.yaml up -d

## Terminate mongoDB

    docker compose -f ./mongo/docker-compose.yaml down

## Use mongoDB client CLI

    docker exec -it mongo mongosh 

    docker exec -it mongo mongosh "mongodb://127.0.0.1:27017" --username 'rizal' --password 'secret'