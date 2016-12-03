# dockerfile_centos_nodejs

This is a Dockerfile for front-end engineers.  
The file builds a Docker Image including CentOS7 + nodebrew + nodejs + npm.  
You can start to develop websites smoothly by using it.

# Example
```sh
$ docker build -t redsnapperrice/centos_nodejs .
$ docker run -it -v /{your local directory}:/home/{your directory} --name {Container NAME} {Image ID}
```

# Docker Hub Repository
[redsnapper/dockerfile_centos_nodejs](https://hub.docker.com/r/redsnapper/dockerfile_centos_nodejs/)

# License
[MIT License](https://github.com/redsnapperrice/dockerfile_centos_nodejs/blob/master/LICENSE)
