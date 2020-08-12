# react-docker-app
A simple ReactJS app with production workflow with Docker

### Setup branch

To run simple react-docker app
 - Build docker image
    `npm run docker:build`
 - Run the built image using
	 `npm run docker:run`
 - This will launch at [http://localhost:3000](http://localhost:3000)

### Docker-compose or main branch
To run the node-redis app with docker compose
 - To build and run
    `npm run compose:build`
 - To only run if it is built
	 `npm run compose:run`
 - To gracefully stop all containers
	 `npm run compose:stop`
 - This will launch at [http://localhost:8080](http://localhost:8080)