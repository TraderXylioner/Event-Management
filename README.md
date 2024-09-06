# Event-Management

## Build project:

``` bash
poetry export -f requirements.txt --output requirements.txt
docker build -t event-manager:0.1 .
docker-compose up
```

## SWAGGER:
http://127.0.0.1:8000/swagger/

### event:
http://127.0.0.1:8000/api/v1/events/

### event reg:

http://127.0.0.1:8000/api/v1/event_registration/

### users:

http://127.0.0.1:8000/api/v1/auth/users/
