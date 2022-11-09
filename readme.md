# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To begin with the development phase, we first need to setup docker, so that we can easily manage the application in-sync with the repository.
To setup Docker :
  1) Download and Install Docker as per your system requirement.
  2) Now navigate to the project root directory and code <sub> docker-compose up</sub>.
  3) Now run http://localhost:3000/api/ping to test out the back-end.

