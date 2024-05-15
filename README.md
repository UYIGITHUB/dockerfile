# dockerfile

This is a docker build file

Customize the official Jenkins Docker image, by executing the following two steps:
A. Create a Dockerfile with the content in dockerfile-for-build
B. Build a new docker image from the Dockerfile, and assign the image a meaningful name, such as "myjenkins-blueocean:2.452.1-1":  docker build -t myjenkins-blueocean:2.452.1-1 .

- run vm
- build docker with docker file form github
- Create a bridge network in Docker
