# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. First, Install [docker](https://docs.docker.com/get-docker/).
2. Validate that docker and docker-compose are working correctly
    `docker -v`
    `docker-compose -v`
3. Start the project running `docker-compose up` in the project's directory.
4. Confirm that the Backend is running. Go to http://localhost:3000/api/ping
5. Confirm that the Frontend is running. Go to http://localhost:3001/register and create an account.


Always run `docker-compose up` when testing stuff. If you need to run a command inside one of the containers try `docker exec`.