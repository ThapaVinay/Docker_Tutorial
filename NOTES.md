# Docker is a tool which is used to make virtual containers from the images.
# Docker image is like a operating system and containers are like machine where these images will run.

# Containers have a separate runtime environment and the changes or things we install or update inside the container will not intevene with things of the machine that the container is running on.

# We have two things docker daemon that does all the things like creating container and stopping them and 
    - Docker desktop that is just used for visualing the status of the docker images and containers.

# Commands of docker:
    - docker container ls : to list all the containers
    - docker start <container-name> : to start any container
    - docker exec <container-name> ls : to run the 'ls' command inside container terminal and return result
    - docker exec -it <container-name> bash : to connect to the container terminal
    - docker images : to see the local images available
    - docker run -it -p 1025:1025 <container-name> : to expose the port of the container to the local machine {port mapping}
    - docker run -it -p 1025:1025 -e key = value -e key = value <container-name> : to pass environment variables to the container
    - docker build -t inotebook . : to build the image from docker file
    - docker login : to login to the docker hub
    - docker push <image-name> : to push to the docker hub

# docker compose   
    it is used to setup, create and destroy multiple containers.
    - docker compose up : all the configuration and services defined in .yml file will be up and running
    - docker compose up -d : to run it in background or detached mode






# Link : https://app.eraser.io/workspace/yTPql82lXyOpbyX63Xgn


