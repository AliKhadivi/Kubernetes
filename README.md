# Kubernetes_training_with_DockerMe
The tools and sample needed to learn the Kubernetes.

# Table and Content

- [Environment Setup:](vagrant)
  - [vagrant and packer](vagrant/vagrant-and-packer.md)
  - [vagrant virtualbox provider](vagrant/vbox-environment)


- [Kubernetes Setup:](setup)
  - [kind config files](setup/kind/kind.md)
  - [kind ingress config](setup/kind/kind-ingress.yml)
  - [kind port mapping config](setup/kind/kind-port-mapping.yml)
  - [kind multi-node custom config](setup/kind/multinode-custom-version.yml)
  - [kubernetes multi-node installation docker](setup/kubeadm/multi-node-installation-docker.md)
  - [kubeadm config docker cri](setup/kubeadm/kubeadm-config-docker.yml)
  - [kubernetes multi-node update](setup/kubeadm/multi-node-update.md)
  - [kubernetes multi-node installation containerd](setup/kubeadm/multi-node-installation-containerd.md)
  - [kubeadm config containerd cri](setup/kubeadm/kubeadm-config-containerd.yml)
  - [RKE kubernetes cluster setup](setup/RKE/rke.md)
  - [RKE kubernetes cluster config](setup/RKE/cluster.yml)


- [Kubernetes Tools:](tools)
  - [kubectl tips](tools/kubectl-tips.md)
  - [kubectl syntax and sample commands](tools/kubectl-command-sample.md)
  - [kubernetes mixin grafana dashboards](tools/kubernetes-mixin/grafana-dashboards)
  - [kubernetes mixin prometheus alerts](tools/kubernetes-mixin/prometheus_alerts.yaml)
  - [kubernetes mixin prometheus rules](tools/kubernetes-mixin/prometheus_rules.yaml)
  - [kubernetes install helm](tools/install-helm.md)
  - [kubernetes manisfest validator](tools/manifest-validator.md)


- [Kubernetes Scenario:](scenario)
  - [etcd backup | restore](scenario/back-restore-etcd.md)
  - [init container](scenario/Init-containers-in-use.md)
  - [kubernetes dns test](scenario/kubernetes-dns-test.md)
  - [kubernetes dashboard](scenario/kubernetes-dashboard.md)
  - [kubernetes portainer dashboard](scenario/portianer-dashboards.md)
  - [kubernetes deployment strategies](scenario/deployment-strategies)
  - [kubernetes logging loki](scenario/loki.md)
  - [kubernetes monitoring prometheus](scenario/prometheus.md)
  - [kubernetes roolout](scenario/rollout-test.md)
  - [kubernetes weavescope deploy](scenario/weavescope.md)
  - [kubernetes wordperss scenario](scenario/wordpress.md)
  - [kubernetes and ceph-csi ](scenario/ceph-csi.md)
  - [kubernetes and bb-csi](scenario/block-bridge-csi.md)
  - [kubernetes sample nginx](scenario/nginx-test)
  - [kubernetes sample app](scenario/sample-app)
  - [kubernetes ingress and cert-manager setup](scenario/ingress-certmanager.md)
  - [kubeapps](scenario/kubeapps.md)
  - [kubernetes backup|restore with velero](scenario/velero.md)
  - [Cassandra with StatefulSets on Kubernetes](https://github.com/kubernetes/examples/tree/master/cassandra)
  - [Create reader user on cluster](scenario/Create-read-only-user-on-cluster.md)
  - [Create reader user on namespace](scenario/Create-read-only-user.md)
  - [Network policy sample](scenario/network-policy.md)
  - [Kubernetes Demo Project](scenario/kubernetes-demo-project.md)

- [Kubernetes Components:](components)
  - [etcd resource check](components/etcd-resource-check.md)
  - [api server audit log](components/api-server-audit-log.md)

- [Kubernetes Manifests:](manifests)
  - [daemonset](manifests/daemonset)
  - [deployment](manifests/deployment)
  - [ingress](manifests/ingress)
  - [job](manifests/job)
  - [namespace](manifests/namespace)
  - [pod](manifests/pod)
  - [security](manifests/security)
  - [service](manifests/service)
  - [statefulset](manifests/statefulset)
  - [storage](manifests/storage)


- [Others:](others)
  - [Phippy and friends](others/Phippy_and_friends)
  - [Kubernetes up & running](others/eBooks/kubernetes-up-running.pdf)
  - [Kubernetes in action](others/eBooks/Kubernetes_in_Action.pdf)


# In Progress Task:
- [ ] Installations:
  - [ ] [etcdadm](https://github.com/kubernetes-sigs/etcdadm)
  - [ ] minikube
  - [ ] k3d
  - [ ] kubespray
  - [x] multi-node new version and with containerd
  - [x] rancher kubernetes engine (RKE)
- [ ] Kubernetes add-ons:
  - [ ] Ingress: nginx
  - [ ] Certificate management: cert-manager
  - [ ] Private registry: harbor
  - [ ] Monitoring: kube-prometheus-stack
  - [ ] Logging: loki stack
  - [ ] Metric Server: kube-metric-server
- [x] pdf and ebook
- [x] HPA
- [x] reader user on cluster
- [x] reader user on namespace
- [x] security manifest

# Reference:
 - https://kubernetes.io
 - https://github.com/kodekloudhub/certified-kubernetes-administrator-course
 - https://brennerm.github.io/posts/kubernetes-overview-diagrams.html
 - https://github.com/ondrejsika/kubernetes-training
 - https://blog.container-solutions.com/kubernetes-deployment-strategies
 - https://github.com/ContainerSolutions/k8s-deployment-strategies
 - https://ranchermanager.docs.rancher.com


# 🔗 Links
[![Site](https://img.shields.io/badge/Dockerme.ir-0A66C2?style=for-the-badge&logo=docker&logoColor=white)](https://dockerme.ir/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-rafiee/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/@rafiee1001)
[![telegram](https://img.shields.io/badge/telegram-0A66C2?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/dockerme)