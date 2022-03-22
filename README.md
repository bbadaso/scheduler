# Interview Scheduler
This is a single-page app built on React.js that allows users to book, edit or cancel interviews for each day of the week (Monday - Friday). Application uses a combination of a concise API with a WebSocket server to build a realtime experience.

Express.js is the basis for the Scheduler API server application.

## Setup
To Run App Locally
Fork this repository & then clone the forked repository.
Go to the scheduler-api that contains the database and fork it & follow the steps to get it up and running.
Install dependencies for both (scheduler & shceduler-api) using the npm install command.
Open two terminals, one for scheduler and the second for scheduler-api.
Run the both servers using the npm start command.
Go to http://localhost:8000/ in your browser and book an interview.

Install dependencies with `npm install`.

## Screenshots
![image](https://user-images.githubusercontent.com/94014416/159563400-fc0e498a-3e55-48c9-930c-447b771a2830.png)
![image](https://user-images.githubusercontent.com/94014416/159563450-d3c568a2-b9b4-46f7-8603-bcd809d287ae.png)


## Running Webpack Development Server

```sh
npm start
```

## Running Jest Test Framework

```sh
npm test
```

## Running Storybook Visual Testbed

```sh
npm run storybook
```
## Project Stack

Front-End: React, Axios, JSX, HTML, SASS

Back-End: Express, Node.js, PostgreSQL, WebSocket

Testing: Cypress, Storybook, Jest, React Testing Library, Webpack Dev Server
