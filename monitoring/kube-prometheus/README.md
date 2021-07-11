#### 2021.04.15 기준
#### 원본: https://github.com/prometheus-operator/kube-prometheus
#### release-0.7 branch
#### 파일 내용 변경된 부분 키워드 MODIFIED-BY-HT 로 검색
````
kubectl create -f 1-prometheus-operator/
kubectl create -f 2-manifests/
kubectl apply -f 3-ingress.yaml
````

#### dev, patch, production 디렉토리 하위의 인그레스 적용 후 접속
````
kubectl apply -f ./[dev|patch|staging]/1-ingress.yaml
````

#### Grafana Dashboard 설치
https://grafana.com/grafana/dashboards?search=kubernetes
