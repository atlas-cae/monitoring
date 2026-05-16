# Grafana Dashboards for HPC monitoring

To deploy, have **Grafana** running, then simple import dashboards by uploading these JSON files.

*Make sure you have prometheus and the exporter services running*

1. General Report -> node_exporter.service
2. Slurm Report -> configure slurm.conf
3. GPU Report -> nvidia/dcgm-exporter

