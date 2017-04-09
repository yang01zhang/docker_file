1.  base_docker_file => base iamge

2.  Dockerfile ==  base image ==> ubuntu_nginx_uwsgi_server

Please see the whole docker file in docker_file .


How to run ubuntu:

	1. docker build -t xagent_django:v0.1 -f Dockerfile . 
        2. docker run -it -d xagent_django:v0.1
	3. docker exec -it container_name /bin/bash
