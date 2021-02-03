```bash
mkdir provision/ansible/roles/
ansible-galaxy role install -r provision/ansible/requirements.yml -p provision/ansible/roles/
ansible-galaxy collection install -r provision/ansible/requirements.yml -p provision/ansible/roles/
vagrant up
```
