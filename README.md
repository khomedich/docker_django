# docker_django
Run Django in docker


####git clone
$ git clone https://github.com/khomedich/docker_django.git

####In the terminal, make sure you're in the docker_django directory.
$ cd /path/to/docker_django

####Build the image.
$ docker build -t docker_django .

####Run your container
$ docker run --name d_d -dp 127.0.0.1:8000:8000 docker_django
