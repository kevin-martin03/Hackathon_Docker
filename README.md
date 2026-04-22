# Hackathon_Docker

Description
Déploiement d'une stack de monitoring Prometheus, Grafana, Node_exporter, Alertmanager.

##
Télécharger le template Grafana avant de lancer docker-compose

mkdir -p grafana/provisioning/dashboards

curl -o grafana/provisioning/dashboards/node-exporter.json \
https://grafana.com/api/dashboards/1860/revisions/latest/download
