## Monitoring Stack
<br>

List of open source monitoring tools & their functions:  

<br>

| Time Series Database | Agent / Data Collector  | Visualize                  | Log Aggregators / Shippers |  Logging |  Alerts      |  Scripting/Query |   
| -------------------- | ----------------------  | ------------------         | -------------------------- | -------- | ------------ | ---------------- |
| Promethues           | Pushgateway<br> Exporters | Grafana, Promethues web UI | Promtail                   | Loki     | AlertManager | PromQL<br> LogQ     |
| Elasticsearch        | Beats → Metricbeat<br> Heartbeat      | Kibana             | Beats → Filebeat<br> Winlogbeat          | Logstash |              |                  |
| InfluxDB             | Telegraf                | Chronograf         |                            |          | Kapacitor    | Flux<br> InfluxQL  |
| OpenTSDB             |                         |                    |                            |          |              |                  |
| Graphite (Whisper & Carbon) | StasD<br> Collectd | Graphite-web       |                            |          |              |                  |
|                      | Fluentbit               |                    | Fluentd                    |          |              |                  |



### Graphite

- carbon : A high-performance service that listens for time-series data
- whisper : A simple database library for storing time-series data
- graphite-web : Graphite's user interface & API for rendering graphs and dashboards

### ELK

- Elasticsearch : Indexing and storage
- Kibana : Analysis and visualization
- Logstash : Data Aggregation and Processing
- Beats : Data Collection

### TICK

- Telegraf : Server agent for collecting and reporting metrics
- InfluxDB : A time series database
- Chronograf : Administrative user interface and visualization engine
- Kapacitor : A native data processing engine