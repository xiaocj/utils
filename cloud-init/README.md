1. multipass运行k8s-master
```
multipass launch -n k8s-master -m 2G -d 10G -c 2 --cloud-init k8s-master.yaml
```