# packer-templates
templates for packer




##### resources

* centos kickstart: https://docs.centos.org/en-US/centos/install-guide/Kickstart2/#sect-kickstart-examples
* ubuntu preseeding https://help.ubuntu.com/lts/installation-guide/amd64/apb.html



```
packer build \
  -var proxmox_node=pve1 \
  -var proxmox_username="root@pam" \
  -var proxmox_password=password \
  -var proxmox_url=https://192.168.0.1:8006/api2/json \
  centos8/packer.proxmox.json
```

examples:

* https://github.com/dustinrue/proxmox-packer
* https://github.com/chriswayg/packer-proxmox-templates/
* https://github.com/Aaron-K-T-Berry/packer-ubuntu-proxmox-template
* https://github.com/geerlingguy/packer-boxes
