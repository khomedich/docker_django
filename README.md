# docker_django
Run Django in docker


####In the terminal, make sure you're in the docker_django directory.
$ cd /path/to/docker_django

####Build the image.
$ docker build -t docker_django .

####Run your container
$ docker run -dp 127.0.0.1:8000:8000 docker_django
