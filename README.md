# Admin Panel with modular monolith

Well hi there! This repository holds the code and script for the Admin Panel with modular monolith

## Setup

If you've just downloaded the code, congratulations!

To get it working, follow these steps:

- `make build` to build the containers
- `make start` to start the containers
- `make stop` to stop the containers
- `make restart` to restart the containers
- `make prepare` to install dependencies with composer (once the project has been created)
- `make run` to start a web server listening on port 1000 (8000 in the container)
- `make logs` to see application logs
- `make ssh-be` to SSH into the application container
