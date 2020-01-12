# kubernetes
that repo contain all the examples and scripts for kubernetes

commands

> kubectl create –f replicaset-definition.yml

> kubectl get replicaset

> kubectl delete replicaset myapp-replicaset *Also deletes all underlying PODs

> kubectl replace -f replicaset-definition.yml

> kubectl scale –replicas=6 -f replicaset-definition.yml

> kubectl create –f deployment-definition.yml --record

> kubectl get deployments

> kubectl apply –f deployment-definition.yml

> kubectl set image deployment/myapp-deployment nginx=nginx:1.9.1

> kubectl rollout status deployment/myapp-deployment

> kubectl rollout history deployment/myapp-deployment

> kubectl rollout undo deployment/myapp-deployment
