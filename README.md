# Challenge 2 - Backend and frontend

In this challenge, I work with both the frontend and the backend to consolidate the knowledge acquired in class.

## Requirements:
- Create a docker-compose.yaml that lifts a Nest.js and React application together
- The Nest.js application needs to run on port 3000
- React.js application needs to run on port 3001
- When accessing http://localhost:3001 the React application needs to consume and list "routes" from the Nest.js endpoint: http://localhost:3000/routes.
- The endpoint http://localhost:3000/routes needs to return 5 routes with the following data: title - route title, startPosition - contains latitude and longitude, endPosition - contains latitude and longitude

## Steps:
1) Clone the repo and go to the folder
2) Run `sudo run.sh` and wait a few seconds
3) Access `localhost:3001` in your browser
