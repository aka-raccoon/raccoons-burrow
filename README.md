# Raccoons Burrow

### K3S Cluster

This document is work-in-progress.

### Steps after provisioning

Stop scheduling pods on kubernetes master

```shell
kubectl taint nodes r8s-master-1 node-role.kubernetes.io/master=:NoSchedule
```
