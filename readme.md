# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

run docker-compose up in your codespace's terminal to load Anythink's backend and frontend.
Once docker-compose finishes loading up, the backend should be running and able to connect to the database.

After the server is up, make sure you test it by pointing your browser to
https://[yourusername]-turbo-tribble-r94v6ggqw9xhv54-3000.preview.app.github.dev/api/ping

Example:
https://yairgg80-turbo-tribble-r94v6ggqw9xhv54-3000.preview.app.github.dev/api/ping