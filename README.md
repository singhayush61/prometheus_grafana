# prometheus_grafana
before running docker compose -f docker-compose-new-optimized up -d
run
Bash
mkdir -p ./shared/tempo ./shared/prometheus ./shared/loki ./shared/alloy ./shared/grafana/provisioning/datasources

curl -L -o ./shared/tempo/tempo.yml https://raw.githubusercontent.com/aussiearef/grafana-udemy/main/tempo/tempo.yml
curl -L -o ./shared/prometheus/prometheus.yml https://raw.githubusercontent.com/aussiearef/grafana-udemy/main/prometheus/prometheus.yml
curl -L -o ./shared/alloy/config.alloy https://raw.githubusercontent.com/aussiearef/grafana-udemy/main/alloy/config.alloy
curl -L -o ./shared/grafana/provisioning/datasources/datasources.yml https://raw.githubusercontent.com/aussiearef/grafana-udemy/main/grafana/datasources.yml
