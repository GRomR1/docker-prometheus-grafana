# docker-prometheus-grafana
Example of running Prometheus and Grafana in Docker for monitoring Spring Boot Java app

1. Edit target in [prometheus.yaml](./docker/config/prometheus.yml)
2. Run Prometheus and Grafana with docker-compose:
```
cd ./docker
docker-compose up
```

# additional 
Scripts to run an app and prometheus in K8s