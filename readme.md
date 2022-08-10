# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:**
1. Clone the repo
1. Install docker https://docs.docker.com/get-docker/
1. Verify docker installation `docker -v` and `docker-compose -v`
1. Run `docker-compose up` in the root directory of the project
1. Verify the backend: `http://localhost:3000/api/ping`
1. Verify the frontend: Make a user at `http://localhost:3001/register`
1. Verify you have been navigated to your new profile
