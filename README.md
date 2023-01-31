# Helm Charts

This repo includes ELK stack i.e. elasticsearch, logstash, kibana, filebeat helm charts for deployment.

>To install this repo in you machine download helm cli, and run command:

```bash
$ helm repo add [local-repo-name] https://kavan-dalwadi.github.io/helm/
e.g. helm repo add elk https://kavan-dalwadi.github.io/helm/
```

>To install any of the ELK charts, run command:

```bash
$ helm install [chart-name] [local-repo-name]/[chart-name]
e.g. helm install logstash elk/logstash
```
