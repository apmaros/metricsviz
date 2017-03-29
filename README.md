# Spike on monitoring and displaying JMX Metrics

## Dependencies:

- Zookeeper
- Kafka
- [Influxdb](https://hub.docker.com/_/influxdb/)
- [Graphana](http://docs.grafana.org/guides/basic_concepts/)
- [JMXTrans](www.jmxtrans.org) 

## Usage

`docker-compose up -d`


## Metrics 

Metrics are collected using JMXTrans and configured in [jmxtrans.config.json](jmxtrans/jmxtrans.config.json). Kafka offers many other metrics described in [documentation](http://docs.confluent.io/3.2.0/kafka/monitoring.html). 

To visualise metrics, you can use example [dashboard](kafka-dashboard.json) for Grafana.
