# Selectors

Taint the node
---

kubectl taint nodes node1 key1=value1:NoSchedule
---
kubectl taint nodes ip-192-168-28-19.ec2.internal hardware=gcp:NoSchedule

Untaint

kubectl taint nodes ip-192-168-44-187.ec2.internal hardware=gpu:NoSchedule-

Label node

kubectl label nodes ip-192-168-44-187.ec2.internal hardware=gpu

Ref: https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes