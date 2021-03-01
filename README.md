## Monitoring Stack
<br>

List of open source monitoring tools & their functions:  

<br>

| Time Series Database | Agent / Data Collector  | Visualize          | Log Aggregators / Shippers |  Logging |  Alerts      |  Scripting/Query |   
| -------------------- | ----------------------  | ------------------ | -------------------------- | -------- | ------------ | ---------------- |
| Promethues           | Pushgateway             | Grafana            | Promtail                   | Loki     | AlertManager | PromQL           |
|                      | Exporters               | Promethues web UI  |                            |          |              | LogQL            |
| Elasticsearch        | Beats → Metricbeat      | Kibana             | Beats → Filebeat           | Logstash |              |                  |
|                      | Beats → Heartbeat       |                    | Beats → Winlogbeat         |          |              |                  |
| InfluxDB             | Telegraf                | Chronograf         |                            |          | Kapacitor    | Flux / InfluxQL  |
| OpenTSDB             |                         |                    |                            |          |              |                  |
| Graphite (Whisper & Carbon) | StasD / Collectd | Graphite-web       |                            |          |              |                  |
|                      | Fluentbit               |                    | Fluentd                    |          |              |                  |

