# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Backend:
1. Install Docker (https://docs.docker.com/get-docker/)
2. Verify docker is ready by using `docker -v` and `docker-compose -v`
3. Run `docker-compose up` from the project root directory
4. Test with opening your browser to http://localhost:3000/api/ping

Frontend:
1. Run http://localhost:3001/register 

Just make sure that you run all scripts on one of the containers created by `docker-compose up`.  Also, you can use `docker exec` to run commands on a running container.

