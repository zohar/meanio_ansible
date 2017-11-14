Ansible bundle for the Mean.io solution 


Usage:

On Ubuntu 16, run this first to get Python2 installed: 
`ansible-playbook -b -i hosts playbooks/python2-bootstrap-ansible.yaml`

Then run: 
```bash
git clone https://github.com/ktarasyuk/meanio_ansible
cd meanio_ansible
ansible-playbook -b -i hosts site.yml
```
