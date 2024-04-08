# Prometheus Grafana applications using container images and docker-compose

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

# Configure Grafana and Prometheus using Kuberntes and helm chart

 - helm repo add prometheus-community https://prometheus-community.github.io/helm-charts && helm repo update

 - helm install monitoring-demo prometheus-community/kube-prometheus-stack
