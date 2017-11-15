### Ansible bundle for the Mean.io solution 


#### Usage:

```bash
git clone https://github.com/ktarasyuk/meanio_ansible
cd meanio_ansible
ansible-playbook -b -i hosts site.yml
```

**Note** for Ubuntu 16.04 Xenial Xerus users:
python2 is broken for this distro, for workaround launch this first:
```bash
ansible-playbook -b -i hosts playbooks/python2-bootstrap-ansible.yaml
```
