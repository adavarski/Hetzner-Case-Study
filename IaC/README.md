# WIP:

Note1: Use terraform (preferred) for IaC for easy create/destroy infrastucture & k8s

Note2: Use ansible/hcloud-cli sctipts/etc. for CM (Configuration Management) if not possible to use only Terraform. 

## Development cluster
- k3s based (preferred)

Examples: 

https://github.com/adavarski/k3s-hcloud-ubuntu

https://github.com/adavarski/k3s-hcloud-fedora


- kubeadm based (not so prefered)

Examples:

https://github.com/adavarski/kubeadm-hcloud-ubuntu

- Rancher/RKE2 based  (not preferred: uses docker not cri-o, needs manual steps for setup via UI currently)

## Production cluster - HA (multi-node)
- k8s based (preferred)
- kubeadm based (not so preferred)
- Rancher/RKE2 based  (not preferred: uses docker not cri-o, needs manual steps for setup via UI currently)
- Kubespray (prefered: note: TF + kubespray:ansible)

