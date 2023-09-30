# enable-longhorn-monitoring-on-prometheus-stack
**enable longhorn monitoring on prometheus-stack**

To monitor Langhorne in Prometheus, you can do the following steps:
Note: It has been tested in Langhorne version 1.5.1.
1- Apply "longhorn-servicemonitor.yaml" file.
```
kubectl apply -f longhorn-servicemonitor.yaml
```

