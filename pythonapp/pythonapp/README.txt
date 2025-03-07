creating docker file for python image

FROM : specifies the base image to use for the docker image

RUN: this runs a command inside the docker container during the build process

COPY:copies files from local file system to the docker image

WORKDIR: this sets the working directory for subsequent commmands in the docker file

CMD: this specifies the command to run when the docker container starts
---------------------------------------------------------------------------
Summary of Docker’s Role in Your Application:
Built a Docker image with your Python app and necessary environment.
Created and ran a container from the image, isolating your app and environment.
Ensured consistency across different machines and environments.
Executed your Python script (app.py) inside the container.
Printed output from the script to the terminal (information about the directory and files).
In essence, Docker helped you package and run your Python application in an isolated, reproducible environment that can be easily shared and deployed.