
kubectl run nginx --image= nginx 



# to Export the deployment yml or replicaset yaml or pod yaml 
you can write the below commands 
kubectl get pod pod1 -o yaml
kubectl get pod pod1 -o json
kubectl get deployment -o yaml 

# Delete all Pods 

