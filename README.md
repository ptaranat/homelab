# homelab

Ansible roles for installing k3s on a Raspberry Pi 4 cluster

## Update OS and packages

```
ansible-playbook -i hosts update-all.yml
```

## Installing k3s

```
ansible-playbook -i hosts provision-k3s.yml
```
