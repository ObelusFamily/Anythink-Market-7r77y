# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To install, clone the repo and run `docker-compose up`. You can verify that docker is installed with `docker -v` and `docker-compose -v`. Once the container is running, you can verify that the backend is working by navigating to [http://localhost:3000/api/ping](http://localhost:3000/api/ping) and that the frontend is working by going to [http://localhost:3001/register](http://localhost:3001/register).
