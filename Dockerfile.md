A Dockerfile is a script used to create a Docker image. It consists of a set of instructions that define the base image, setup, configurations, and other components required for an application to run within a Docker container. Here are some common commands used in a Dockerfile:

```sh
1. `FROM`: Specifies the base image for the new image.
   ```
   FROM <image>:<tag>
   ```

2. `LABEL`: Adds metadata to the image.
   ```
   LABEL <key>=<value> <key>=<value> ...
   ```

3. `ENV`: Sets environment variables inside the container.
   ```
   ENV <key>=<value>
   ```

4. `RUN`: Executes a command during image build.
   ```
   RUN <command>
   ```

5. `WORKDIR`: Sets the working directory for subsequent commands.
   ```
   WORKDIR /path/to/directory
   ```

6. `COPY` or `ADD`: Copies files/directories from the build context into the image.
   ```
   COPY <src> <dest>
   ADD <src> <dest>
   ```

7. `EXPOSE`: Declares the ports on which the container will listen.
   ```
   EXPOSE <port> [<port>/<protocol>...]
   ```

8. `CMD`: Specifies the default command to run when a container is started.
   ```
   CMD ["executable", "param1", "param2"]
   CMD command param1 param2
   ```

9. `ENTRYPOINT`: Configures a container to run as an executable.
   ```
   ENTRYPOINT ["executable", "param1", "param2"]
   ```

10. `VOLUME`: Creates a mount point for external volumes.
    ```
    VOLUME /path/to/volume
    ```

11. `USER`: Sets the user or UID to use when running the image.
    ```
    USER <username | UID>
    ```

12. `ARG`: Defines build-time variables that can be passed to the builder with the `docker build` command.
    ```
    ARG <name>[=<default value>]
    ```

13. `ONBUILD`: Defines a command that will be executed when the image is used as a base for another image.

14. `HEALTHCHECK`: Defines a command to periodically check the container's health status.

15. `SHELL`: Sets the default shell for executing RUN commands.

```

These are some of the commonly used commands in a Dockerfile. The Dockerfile syntax and available instructions might change over time with updates to Docker and related tools, so it's always a good idea to refer to the official Docker documentation for the most up-to-date information.
