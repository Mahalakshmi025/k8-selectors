# k8-selectors
Taint the Node

````
kubectl taint nodes <node-ip> key1=value1:NoSchedule
for ex
kubectl taint nodes ip-192-168-19-213.ec2.internal hardware=gpu:NoSchedule

````

label the node

```
kubectl label nodes <node -name > disktype=ssd

if u want to go the pod to only tained node use this for ex,

kubectl label nodes ip-192-168-19-213.ec2.internal hardware=gpu