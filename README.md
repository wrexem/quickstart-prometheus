# Quickstart for Prometheus

Get up and running with Prometheus and node-exporter with a `docker-compose.yml` file in less than 5 minutes.

### special notes: user/group id for grafana is 472, prometheus is 65534
So in this case:
`mkdir grafana_data && chown 472:472 grafana_data`
and
`mkdir data && data && chown 65534:65534 data`

### Running the example
```
$ git clone https://github.com/wrexem/quickstart-prometheus
$ cd quickstart-prometheus
$ docker-compose up -d
```
Open a browser and point at http://localhost:9094/

### See also:

* [Node Exporter](https://github.com/prometheus/node_exporter)

* [Querying Promtheus](https://prometheus.io/docs/querying/basics/)

