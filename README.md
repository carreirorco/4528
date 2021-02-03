```bash
git clone https://github.com/carreirorco/4528.git
cd 4528
mkdir provision/ansible/roles/
ansible-galaxy role install -r provision/ansible/requirements.yml -p provision/ansible/roles/
ansible-galaxy collection install -r provision/ansible/requirements.yml -p provision/ansible/roles/
vagrant up
```
