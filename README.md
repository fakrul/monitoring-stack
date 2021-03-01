## Monitoring Stack
<br>

List of open source monitoring tools & their functions:  

<br>

| Time Series Database | Agent / Data Collector  | Visualize                  | Log Aggregators / Shippers |  Logging |  Alerts      |  Scripting/Query |   
| -------------------- | ----------------------  | ------------------         | -------------------------- | -------- | ------------ | ---------------- |
| Promethues           | Pushgateway<br> Exporters | Grafana, Promethues web UI | Promtail                   | Loki     | AlertManager | PromQL<br> LogQ     |
| Elasticsearch        | Beats → Metricbeat<br> Beats → Heartbeat      | Kibana             | Beats → Filebeat<br> Beats → Winlogbeat          | Logstash |              |                  |
| InfluxDB             | Telegraf                | Chronograf         |                            |          | Kapacitor    | Flux<br> InfluxQL  |
| OpenTSDB             |                         |                    |                            |          |              |                  |
| Graphite (Whisper & Carbon) | StasD<br> Collectd | Graphite-web       |                            |          |              |                  |
|                      | Fluentbit               |                    | Fluentd                    |          |              |                  |

