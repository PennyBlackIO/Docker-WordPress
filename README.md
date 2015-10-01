# Docker-WordPress
How we implemented WordPress using Docker containers 


Setup Docker Environment 
------
curl -sSL https://get.docker.com/ | sh

Adjust DNS Settings for Docker to use OpenDNS 
-------
sudo vi /etc/default/docker

DOCKER_OPTS="--dns 208.67.222.222 --dns 208.67.220.220 --dns 8.8.8.8 --dns 127.0.0.1"

Make sure docker starts on boot
------
sudo systemctl enable docker 


Setup WordPress
------
