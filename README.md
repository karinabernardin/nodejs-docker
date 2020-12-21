# nodejs-docker

- project executing locally: run `node server.js` and go to http://localhost:3000.

- docker file created. To build docker image: `docker build -t nodejs-docker .`. The image ID can be obtained from `docker images`. to build the container using the created image: `docker run -p 80:3000 {image-id}`. To see docker containers: `docker container ls`. To stop the container: `docker stop {container-id}`.