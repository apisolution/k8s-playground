# k8s-playground

Kubernetes playground for you.

---

### Requirements

- Helm v3.7.1
- Minikube v1.24.0
- Kubectl v1.22.0

Minikube addons must be enabled:

- ingress
- ingress-dns

# Services

Available service for install. For running services with ingress, need to add the ingress URL to `/etc/hosts`.

| Service       | Docker image  | Cluster url                           | Credentials                                    | Ingress url               | 
|---------------|---------------|---------------------------------------|------------------------------------------------|---------------------------|
| MySQL 8       | 8.0.29-debian | mysql.default.svc.cluster.local       | - USER: root<br/>- PASS: root<br/>- PORT: 3306 |                           |
| Redis 7       | 7.0.1-alpine  | redis.default.svc.cluster.local       | - PORT: 6379                                   |                           |
| Redis Stack 7 | 7.0.0-RC5     | redis-stack.default.svc.cluster.local | - PORT: 6379                                   |                           |
| Adminer       | full          |                                       |                                                | http://adminer.k8s.local/ |

