soldesk.kubernetes
This collection automates the setup and management of Kubernetes clusters. Created by the infraninjas team at soldesk.

Warning: Version Compatibility
Please note that the versions of Kubernetes, Calico, and containerd are hardcoded in this collection. You must carefully check these versions before using the cikkectuib ub a production environment to avoid compatibility issues.

Kubernetes Version: v1.30.11
Calico Version: v3.25.0
containerd Version: 1.7.25
It is recommended to adjust these versions manually if necessary to match your environment's requirements.

Requirements
Ansible 2.9+
Kubernetes cluster
Docker
Installation
To install this collection, use the following command:

```bash ansible-galaxy collection install soldesk.kubernetes
