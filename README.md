# PiHole-DockerConfig
Various docker and config files used to spin up a working copy of pihole with a grafana dashboard

It took me hours to get all of this figured out, so I figured I would try and help out the next person that wants to get all of this up and running.

This set of config files will get the following docker containers up and running:
(assumes you already have Pi-Hole running)

- PiHole-Exporter
  - https://github.com/eko/pihole-exporter
- Prometheus
  - https://prometheus.io/docs/prometheus/latest/installation/
  - https://hub.docker.com/r/prom/prometheus/
- Grafana
  - https://grafana.com/docs/grafana/latest/installation/docker/
  - https://hub.docker.com/r/grafana/grafana/

Note...
To get this up and running, make sure you edit the docker-compose.yml file with the IP address and password for your Pi-Hole server.
