# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. Clone the repo - https://github.com/ObelusFamily/Anythink-Market-qz51o
2. Install Docker and SWL 2 server
3. Verify if installation is successful or not using the following commands - docker -v and docker-compose -v
6. Now run this command from project root directory - docker-compose up
 Backend verification -  http://localhost:3000/api/ping
Frontend verification -  http://localhost:3001/register
