# Starts Prometheus Grafana applications using their container images and docker-compose

pre-requisite
 - Docker, Docker-compose installed already - refer - https://github.com/piseganesh123/k8s-installation/tree/main/labenv-doc-compose

enabled permission on config files

sudo chmod -R 777 ./configs/*

Start prometues grafana

docker-compose up -d

access Grafana using 

http://host-machine-ip:3000

access prometues using 

http://host-machine-ip:9000