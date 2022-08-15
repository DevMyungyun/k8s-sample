#### 2021.04
#### Org : https://github.com/prometheus-operator/kube-prometheus
#### release-0.7 branch
````
kubectl create -f 1-prometheus-operator/
kubectl create -f 2-manifests/
kubectl apply -f 3-ingress.yaml
````

#### dev, patch, production access blow options
````
kubectl apply -f ./[dev|patch|staging]/1-ingress.yaml
````

#### Grafana Dashboard install
https://grafana.com/grafana/dashboards?search=kubernetes
