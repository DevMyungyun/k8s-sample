# k8s-sample
Kubernetes YAML Examples to deploy a containerized applications.

## K8S Yaml File List
| Directory             | Description                                                           | Kinds                                                                 |
| ---------             | -----------                                                           | -----------                                                           |
| ./app-node            | Node.JS Yaml files                                                    | - Ingress<br/>- Service<br/>- Pod                                                 |
| ./app-spring          | Spring Boot Yaml files                                                | - Ingress<br/>- Service<br/>- Deployment                                          |
| ./app-volume          | Pod connected to Volume Yaml files                                    | - Ingress<br/>- Service<br/>- Deployment<br/>- Volume                                  |
| ./database            | Database Yaml files<br />- MySQL<br />- PostgreSQL                                | - ConfigMap<br/>- Secret<br/>- Ingress<br/>- Service<br/>- Pod<br/>- Volume                      |
| ./deploy            | Jenkins Yaml files                          | - ServiceAccount<br/>- Role<br/>- RoleBinding<br/>- Ingress<br/>- Service<br/>- Deployment<br/>- Volume                      |
| ./ingress-nginx    | Ingres Nginx Customized Yaml files for Baremetal Server                   | Refer to Annotaion "MODIFIED" in Yaml file                                                     |
| ./externa-resource    | The Endpoint to connect to service out of Kubernetes                  | - Service<br/>- Endpoint                                                     |
| ./monitoring          | Log Monitoring Solutions Yaml and configuration files<br/>- filebeat<br/>- logstash  | - ServiceAccount<br/>- ClusterRole<br/>- ClusterRoleBinding<br/>- ConfigMap<br/>- DaemonSet |
| ./solution            | Solutions Yaml files<br/> - kafka<br/>- keycloak<br/>- zookeeper<br/>- RabbitMQ<br/>- Redis                | - Ingress<br/>- Service<br/>- Deployment<br/>- Statefulset                             |


