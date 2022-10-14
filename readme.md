# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
# To successfully load Anythink's frontend and backend follow these steps:
- Install Docker and verify its installation by running the following commands in your terminal: `docker -v` and `docker-compose -v`.
- Then, run `docker-compose up` from the project root directory.
- The app's backend should be up and running first and to test this visit [this link](http://localhost:3000/api/ping)
- If succesful there should be a message that reads: `"Pong! Seems like Everythink is working, great job!"}`
- Now, it’s time to check the frontend and make sure it’s connected to the backend.
- If everything is working properly, you’ll be able to create a new user [here](http://localhost:3001/register)
