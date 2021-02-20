# packer-templates

templates for packer

* rhel 8 for proxmox VM 🚧
* rhel 8 for vagrant@virtualbox box 🚧
* debian 10  for proxmox VM 🚧
* debian 10  for vagrant@virtualbox box 🚧
* ubuntu 20.04 for proxmox VM 🚧
* ubuntu 20.04 for vagrant@virtualbox box ✅

## Requirements

The following software must be available:

  - [Packer](http://packer.io/)
  - [Vagrant](http://vagrantup.com/)
  - [VirtualBox](https://virtualbox.org/)
  - [Ansible](https://ansible.com)

## Usage

```console
  # example for ubuntu 20.04 for vagrant@virtualbox
felix@bandonga:~$ cd ubunutu20
felix@bandonga:~$ packer build -var-file="variables.json" packer-virtualbox.json
felix@bandonga:~$ vagrant up
felix@bandonga:~$ vagrant ssh
```

### References

* https://github.com/dustinrue/proxmox-packer
* https://github.com/geerlingguy/packer-boxes

