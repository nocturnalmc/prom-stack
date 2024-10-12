### https://kifarunix.com/monitor-docker-swarm-service-metrics-using-grafana/ https://kifarunix.com/monitor-docker-containers-metrics-using-grafana/

### cAdvisor https://github.com/google/cadvisor

### Prometheus https://prometheus.io/docs/prometheus/latest/installation/ https://rokpoto.com/adding-health-check-to-prometheus/

### Grafana https://grafana.com/docs/grafana/latest/setup-grafana/configure-grafana/#override-configuration-with-environment-variables https://grafana.com/tutorials/run-grafana-behind-a-proxy/#configure-nginx

1. cp .env.example .env
2. docker run cadvisor-$(hostname)
3. edit prometheus.yml targets
4. docker compose up -d
