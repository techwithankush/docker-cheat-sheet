Here's the comprehensive list of Docker commands 🥇

```sh

# Attach local standard input, output, and error streams to a running container
docker attach CONTAINER

# Build an image from a Dockerfile
docker build -t IMAGE_NAME:TAG PATH

# Manage builds
docker builder COMMAND

# Manage checkpoints
docker checkpoint COMMAND

# Create a new image from a container’s changes
docker commit CONTAINER NEW_IMAGE_NAME

# Manage Swarm configs
docker config COMMAND

# Manage containers
docker container COMMAND

# Manage contexts
docker context COMMAND

# Copy files/folders between a container and the local filesystem
docker cp SRC_PATH CONTAINER:DEST_PATH
docker cp CONTAINER:SRC_PATH DEST_PATH

# Create a new container
docker create IMAGE_NAME

# Inspect changes to files or directories on a container’s filesystem
docker diff CONTAINER

# Get real-time events from the server
docker events

# Execute a command in a running container
docker exec -it CONTAINER COMMAND

# Export a container’s filesystem as a tar archive
docker export CONTAINER > FILENAME.tar

# Show the history of an image
docker history IMAGE_NAME

# Manage images
docker image COMMAND

# List images
docker images

# Import the contents from a tarball to create a filesystem image
docker import FILENAME.tar NEW_IMAGE_NAME

# Display system-wide information
docker info

# Return low-level information on Docker objects
docker inspect OBJECT

# Kill one or more running containers
docker kill CONTAINER

# Load an image from a tar archive or STDIN
docker load < FILENAME.tar

# Log in to a registry
docker login [OPTIONS] [SERVER]

# Log out from a registry
docker logout [SERVER]

# Fetch the logs of a container
docker logs CONTAINER

# Manage Docker image manifests and manifest lists
docker manifest COMMAND

# Manage networks
docker network COMMAND

# Manage Swarm nodes
docker node COMMAND

# Pause all processes within one or more containers
docker pause CONTAINER

# Manage plugins
docker plugin COMMAND

# List port mappings or a specific mapping for the container
docker port CONTAINER

# List containers
docker ps [OPTIONS]

# Download an image from a registry
docker pull IMAGE_NAME

# Upload an image to a registry
docker push IMAGE_NAME

# Rename a container
docker rename OLD_NAME NEW_NAME

# Restart one or more containers
docker restart CONTAINER

# Remove one or more containers
docker rm CONTAINER

# Remove one or more images
docker rmi IMAGE_NAME

# Create and run a new container from an image
docker run [OPTIONS] IMAGE_NAME

# Save one or more images to a tar archive
docker save IMAGE_NAME > FILENAME.tar

# Search Docker Hub for images
docker search IMAGE_NAME

# Manage Swarm secrets
docker secret COMMAND

# Manage Swarm services
docker service COMMAND

# Manage Swarm stacks
docker stack COMMAND

# Start one or more stopped containers
docker start CONTAINER

# Display a live stream of container(s) resource usage statistics
docker stats CONTAINER

# Stop one or more running containers
docker stop CONTAINER

# Manage Swarm
docker swarm COMMAND

# Manage Docker
docker system COMMAND

# Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE
docker tag SOURCE_IMAGE TARGET_IMAGE

# Display the running processes of a container
docker top CONTAINER

# Manage trust on Docker images
docker trust COMMAND

# Unpause all processes within one or more containers
docker unpause CONTAINER

# Update configuration of one or more containers
docker update CONTAINER

# Show the Docker version information
docker version

# Manage volumes
docker volume COMMAND

# Block until one or more containers stop, then print their exit codes
docker wait CONTAINER


```
