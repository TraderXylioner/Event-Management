# Event-Management

Python (Django) test task
Develop a Django REST-Api for Event Management
The primary goal of this task is to create a Django-based REST-Api that manages
events (like conferences, meetups, etc.). The application will allow users to create,
view, update, and delete events. It should also handle user registrations for these
events.

Key Requirements
- [x] Design an Event model with fields such as title, description, date, location,
and organizer. 
- [x] Implement CRUD (Create, Read, Update, Delete) operations for the Event
model.
- [x] Basic User Registration and Authentication.
- [x] Event Registration
- [x] API documentation
- [x] Docker
- [x] Readme file

Bonus Points
- [ ] Implement an advanced feature like event search or filtering.
- [ ] Add a feature for sending email notifications to users upon event registration.

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
