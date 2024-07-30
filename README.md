# wsl2-microk8s-lab
This repo contains Kubernetes/Cloud native tools that will be deployed on microk8s cluster running on WSL2

### Infra needs:
- WSL2: wsl2 lets a windows user use a virtual linux environment on Windows Machine itself. This is pretty handy feature for quick development needs on your local machine. See [Install WSL2](https://learn.microsoft.com/en-us/windows/wsl/install) to get started.

- Microk8s: Microk8s is a low-ops, lightweight upstream kubernetes solution. See [Install Microk8s](https://microk8s.io/docs/getting-started) to get started.

### LoadBalancer needs:
- MetalLB: A network LB implementation that tries to “just work” on bare metal clusters. See [Enable MetalLB Addon](https://microk8s.io/docs/addon-metallb)

*NOTE: While enabling the addon make sure to provide the subnet/range of IP that falls within your local network*

### LAB STACK:
- Declartive Delivery tool: We will use ArgoCD to deploy applications on our Microk8s Cluster see [Delivery Tool](https://github.com/lamadome/wsl2-microk8s-lab/tree/main/delivery-tool#readme) for details.


