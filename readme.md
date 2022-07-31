# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
The first step is to open Git in the Anything Market repository
Afterwards, utilize the command docker-compose up and wait for the app to start up.
Afterwards you can check if the startup was successful by visting http://localhost:3000/api/ping
Lastly, check if the frontend was connected to the backend by seeing if you can create an account.


**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
