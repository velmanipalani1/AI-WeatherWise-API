# AI WeatherWise – Project Design

## Architecture
The backend follows an MVC-oriented architecture with controllers, models, routing, middleware, services and a MongoDB data layer.

## Main Entities
### User
- _id
- name
- email
- password
- role

### Location
- _id
- user
- city
- country
- createdAt

## Relationship
One registered user can save multiple favorite locations.

See the image files in this folder for the system architecture, ER diagram, user workflow and MVC architecture.
