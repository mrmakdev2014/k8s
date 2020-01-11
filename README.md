# kubernetes
that repo contain all the examples and scripts for kubernetes

commands

> kubectl create –f replicaset-definition.yml

> kubectl get replicaset

> kubectl delete replicaset myapp-replicaset *Also deletes all underlying PODs

> kubectl replace -f replicaset-definition.yml

> kubectl scale –replicas=6 -f replicaset-definition.yml

