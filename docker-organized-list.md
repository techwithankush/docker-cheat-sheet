
Here's the list of Docker commands, organized into logical categories:

**Container Management:**

```plaintext
# Create a new container
docker create IMAGE_NAME

# Execute a command in a running container
docker exec -it CONTAINER COMMAND

# Pause all processes within one or more containers
docker pause CONTAINER

# Unpause all processes within one or more containers
docker unpause CONTAINER

# Start one or more stopped containers
docker start CONTAINER

# Stop one or more running containers
docker stop CONTAINER

# Restart one or more containers
docker restart CONTAINER

# Remove one or more containers
docker rm CONTAINER

# Kill one or more running containers
docker kill CONTAINER

# Update configuration of one or more containers
docker update CONTAINER

# Attach local standard input, output, and error streams to a running container
docker attach CONTAINER

# Display the running processes of a container
docker top CONTAINER

# Fetch the logs of a container
docker logs CONTAINER

# List port mappings or a specific mapping for the container
docker port CONTAINER

# Display a live stream of container(s) resource usage statistics
docker stats CONTAINER

# Inspect changes to files or directories on a container’s filesystem
docker diff CONTAINER

# Copy files/folders between a container and the local filesystem
docker cp SRC_PATH CONTAINER:DEST_PATH
docker cp CONTAINER:SRC_PATH DEST_PATH
```

**Image Management:**

```plaintext
# Build an image from a Dockerfile
docker build -t IMAGE_NAME:TAG PATH

# Create a new image from a container’s changes
docker commit CONTAINER NEW_IMAGE_NAME

# List images
docker images

# Show the history of an image
docker history IMAGE_NAME

# Manage images
docker image COMMAND

# Import the contents from a tarball to create a filesystem image
docker import FILENAME.tar NEW_IMAGE_NAME

# Load an image from a tar archive or STDIN
docker load < FILENAME.tar

# Upload an image to a registry
docker push IMAGE_NAME

# Remove one or more images
docker rmi IMAGE_NAME

# Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE
docker tag SOURCE_IMAGE TARGET_IMAGE

# Save one or more images to a tar archive
docker save IMAGE_NAME > FILENAME.tar

# Search Docker Hub for images
docker search IMAGE_NAME
```

**Registry and Login:**

```plaintext
# Pull an image from a registry
docker pull IMAGE_NAME

# Log in to a registry
docker login [OPTIONS] [SERVER]

# Log out from a registry
docker logout [SERVER]
```

**System Information:**

```plaintext
# Display system-wide information
docker info

# Return low-level information on Docker objects
docker inspect OBJECT

# Display the Docker version information
docker version

# Manage Docker
docker system COMMAND
```

**Network and Volume Management:**

```plaintext
# Create a new network
docker network create NETWORK_NAME

# Remove one or more networks
docker network rm NETWORK

# Connect a container to a network
docker network connect NETWORK CONTAINER

# Disconnect a container from a network
docker network disconnect NETWORK CONTAINER

# List networks
docker network ls

# Display detailed information about a network
docker network inspect NETWORK

# Create a new volume
docker volume create VOLUME_NAME

# Remove one or more volumes
docker volume rm VOLUME

# List volumes
docker volume ls

# Display detailed information about a volume
docker volume inspect VOLUME

# Prune unused volumes
docker volume prune

```

**Swarm and Service Management:**

```plaintext
# Manage Swarm
docker swarm COMMAND

# Manage Swarm nodes
docker node COMMAND

# Manage Swarm services
docker service COMMAND

# Manage Swarm stacks
docker stack COMMAND
```

**Other Commands:**

```plaintext
# Manage builds
docker builder COMMAND

# Manage checkpoints
docker checkpoint COMMAND

# Manage contexts
docker context COMMAND

# Create and run a new container from an image
docker run [OPTIONS] IMAGE_NAME

# Display real-time events from the server
docker events

# Export a container’s filesystem as a tar archive
docker export CONTAINER > FILENAME.tar

# Manage Docker image manifests and manifest lists
docker manifest COMMAND

# Manage plugins
docker plugin COMMAND

# Show the Docker version information
docker version

# Block until one or more containers stop, then print their exit codes
docker wait CONTAINER
```

Feel free to use this organized list of Docker commands with explanations for easy reference.
