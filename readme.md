# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

In order to run the project you have to install ([Docker](https://docs.docker.com/get-docker/). Verify that it wasy properly installed by running `docker -v` and `docker-compose -v`.

Now, go to the project's root directory and run `docker-compose up`, this will load the frontend and the backend of Anythink.
Point your browser to http://localhost:3000/api/ping to see if the backend is running, and then open http://localhost:3001/register to see that the frontend is running and to create your Anythink user.
