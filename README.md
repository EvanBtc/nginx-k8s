# Nginx app on Kubernetes cluster
Deploy nginx app on Kubernetes cluster, with 3 nodes (k3s). We can have access to nginx website on the node's adress ip on the port 30001.

## Autoscaling
Autoscaling when the cpu utilization is up to 25%, we allow 10 application replicas. With a 3 minimum replicas.

## Affinity and AntiAffinity rules
Rules to allow only node with the tag City and value : Paris, Londres and Montreal can accommodate pods.

---
Evan BITIC - Alexis DOUANNES
