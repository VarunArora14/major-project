## Install Docker Image via Dockerhbu

https://hub.docker.com/r/rdxdocker14/varun-major-project

You can skip to **Running the Project** if this part is completed, otherwise you can build the image
## Building docker image from source instead
Inorder to run this project you must have docker daemon started by either docker desktop or command line(in linux) 
To start the project, run the following commands

RUN `docker build -t varun-major-project .` - This will take around 2 minutes to build the image

Once the image is built, 
RUN `docker images` to check the current image named `major-project`

## Running the Project

Then to start a container with this image, type the following command
`docker run -d -p5000:5000 rdxdocker14/varun-major-project`

This will start the container and project is now visible at port 5000.
For this type url in BROWSER `localhost:5000` to start the project