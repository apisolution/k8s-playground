# k8s-playground

Kubernetes playground for you.

---

### Requirements

- Helm v3.7.1
- Minikube v1.24.0
- Kubectl v1.22.0

# Services

Available service for install

| Service       | Docker image  | Cluster url                           | Credentials                                    | 
|---------------|---------------|---------------------------------------|------------------------------------------------|
| MySQL 8       | 8.0.29-debian | mysql.default.svc.cluster.local       | - USER: root<br/>- PASS: root<br/>- PORT: 3306 |
| Redis 7       | 7.0.1-alpine  | redis.default.svc.cluster.local       | - PORT: 6379                                   |
| Redis Stack 7 | 7.0.0-RC5     | redis-stack.default.svc.cluster.local | - PORT: 6379                                   |
