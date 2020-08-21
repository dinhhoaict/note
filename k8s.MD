Enable SCTP Support in k8s

Tren master node:
 - vi /etc/kubernetes/manifests/kube-apiserver.yaml
Add feature gate:
 - --feature-gates=SCTPSupport=true
