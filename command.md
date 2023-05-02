
Docker version = `docker` or `docker - - version`
Docker credential = `docker login` or `docker logout`

Add basic docker command into [“Dockerfile”]


To package our application with docker build = `docker build -t [local repo name] .`

Show all the docker images on your computer = `docker images` or `docker image ls` (ls is short for list)

Run docker application = `docker run [local repo name]` (You can run this command from any directory)

To push your local docker image into the docker hub first, create a repository into your docker hub account then login docker hub by CLI command (point no.2).  

First, create an instance of your local docker image with the same name as your docker hub `username/repository-name`  by using this command = `docker tag [local repo name]:latest username/repository-name:[v1, v2..]`

Then push the local repo by this command = `docker push username/repository-name:[v1, v2,..]`








