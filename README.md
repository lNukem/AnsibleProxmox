# Proxmox Virtual Environment on Debian 12
## Ansible deployment PVE on Debian

### Extra Vars
- ##### target_server_ip
- ##### target_server_hostname
- ##### pve_dns_name

### Installation

```
ansible-playbook playbooks/proxmox_8_install.yml --extra-vars "target_server_ip={IP_address} target_server_hostname={Hostname} pve_dns_name={DNSname}" -u root --ask-pass root
```
