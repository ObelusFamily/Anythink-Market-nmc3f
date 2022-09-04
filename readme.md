# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Download Docker
2. Download Git repo https://github.com/ObelusFamily/Anythink-Market-nmc3f
3. Clone the Git repo to your computer
4. Open command prompt and navigate to directory you cloned the Git repo to
5. Type and enter: docker-compose up
Note: This may take several minutes to complete
6. Check the backend is running by opening a web browser to http://localhost:3000/api/ping
You should see a message that it's working
7. Check the frontend is running by opening a web browser to http://localhost:3001/register
8. Go ahead and register as a user