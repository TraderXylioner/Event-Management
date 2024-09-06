# Event-Management

# Build project:

``` bash
poetry export -f requirements.txt --output requirements.txt
docker build -t event-manager:1.0 .
docker-compose up
```