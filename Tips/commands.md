# Create new pod with deployments and replica set on the fly
kubectl run nginx --image=nginx --generator=run-pod/v1

# To terminiate the pod , replica and deployment create using the above command use the following command

kubectl run nginx --image=nginx --generator=run-pod/v1

# Q: what's the difference between the above command and the below one
kubectl run nginx --image= nginx 

# "this command just create pod but the first one create complete deployment with replica set 

-------------------

