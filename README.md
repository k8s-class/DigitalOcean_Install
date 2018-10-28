# kubeadm
How to install on prem or non-cloud supported environment

Kubeadm works on any deb/rpm based linux system.
    Create a minimum of two droplets, one for master and one for worker node.
    Minimum of 2GB Ram for each node.
    Can use public or private IP Addressing.
    Recommended to use a firewall on public IP Addresses.


    For master node.
    scripts/create-user.sh
    scripts/install-kubernetes.sh

    For worker node.
    scripts/create-user.sh
    scripts/install-node.sh
