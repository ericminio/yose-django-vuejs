````
docker-compose up -d yosethegame
docker-compose run --rm --service-ports player
...
````

- open http://localhost:5000
- create player
- play with server http://host.docker.internal:5001