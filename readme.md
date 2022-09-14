# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Below are the steps to setup the project locally

1) Clone the repo (Do not fork it please)
2) Ensure you have docker compose locally [Docker](https://docs.docker.com/compose/install)
    - You can check the installation using the command `docker -v` and `docker-compose -v`
3) Start the backend and frontend from the container using the command `docker-compose up`
    - The backend will be mapped to the port `3000` and the frontend on port `3001`

Enjoy 😀

