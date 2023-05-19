# GoCRUD-RestAPI

GO CRUD Rest API using Mux, Postgres, Docker, and Docker Compose

## Prerequisites

Make sure you have the following installed on your system:

- Go (version 1.19)
- Docker
- Docker Compose
- Postgres (version 12)

## Installation

1. Clone this repository to your machine:

```bash
git clone https://github.com/ModaxDev/GoCRUD-RestAPI/tree/master
```

## Navigate to the project directory:

```bash
cd GoCRUD-RestAPI
```

## Start the development environment using Docker Compose:

```bash
docker compose build
```

This will build the Docker containers for the GoCRUD Rest API application and Postgres database and run them locally.

## Once the containers are up and running, you can access the API at the following URL:

```bash
http://localhost:8000
```

## API Endpoints
### The API exposes the following endpoints:

- GET /users: Retrieves all users
- GET /users/{id}: Retrieves a single user by id
- POST /users: Creates a new user
- PUT /users/{id}: Updates a user by id
- DELETE /users/{id}: Deletes a user by id

## License
This project is licensed under the MIT License.