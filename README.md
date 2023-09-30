# enable-longhorn-monitoring-on-prometheus-stack
**enable longhorn monitoring on prometheus-stack**

To monitor Langhorne in Prometheus, you can do the following steps:
Note: It has been tested in Langhorne version 1.5.1.
1- Apply "longhorn-servicemonitor.yaml" file for creating longhorn service monitor.

```
kubectl apply -f longhorn-servicemonitor.yaml
```

![image](https://github.com/IMAN-NAMJOOYAN/enable-longhorn-monitoring-on-prometheus-stack/assets/16554389/51196864-4702-4d3c-aac7-346ca792c8ae)


![image](https://github.com/IMAN-NAMJOOYAN/enable-longhorn-monitoring-on-prometheus-stack/assets/16554389/ecd4fdcb-c77f-44ec-9df9-78b20c4999b9)


2- Apply "longhorn-alertmanager.yaml" file for creating alert for longhorn alertmanager.

```
kubectl apply -f longhorn-alertmanager.yaml
```
![image](https://github.com/IMAN-NAMJOOYAN/enable-longhorn-monitoring-on-prometheus-stack/assets/16554389/0e5641d0-2525-4aeb-8ca8-f7c50702f70b)


3- Create longhorn dashboard from "https://grafana.com/grafana/dashboards/16888-longhorn/".

![image](https://github.com/IMAN-NAMJOOYAN/enable-longhorn-monitoring-on-prometheus-stack/assets/16554389/da4bc3c4-ceb3-416b-a8ea-ba5db92b2691)


