# simple docker flask application

----


## Build Application

Build the docker image manually by cloning the git repository
> $ git clone https://github.com/mnaustria/docker.git
> $ docker build -t mnaustria/simple-flask-docker:v0.1 .

 ## Run Application

Create a container from the image.

> $ docker run -d -p 5000:5000 mnaustria/simple-flask-docker:v0.1

Notes:

'-d' to allow the container from the background

'-p' to expose the port 

Now Visit http://localhost:5000

