# k8-selectors
Taint the Node

````
kubectl taint nodes <node-ip> key1=value1:NoSchedule
for ex
kubectl taint nodes ip-192-168-19-213.ec2.internal hardware=gpu:NoSchedule

````