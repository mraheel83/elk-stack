# ELK stack

This stack consists of elastic services:

- Logstash
- Filebeat
- Kibana desktop
- Elasticsearch

This project is based on helm and their charts and templates will be managed in their separate directories.

## Logstash

```
helm install logstash .
helm uninstall logstash
```

## Filebeat

```
helm install filebeat .
helm uninstall filebeat
```

## Kibana desktop

```
helm install kibana .
helm uninstall kibana
```

## Elasticsearch

```
helm install elasticsearch .
helm uninstall elasticsearch
```

## Trobleshooting

- kubectl get pods
- kubectl get services
- kubectl logs `container`
- kubectl describe pod `container`
