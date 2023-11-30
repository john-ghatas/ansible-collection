# Getting Started

To get started install Ansible, this can be done in different ways

## Install Ansible

There is 2 ways to install Ansible, in the case of Fedora the package is easy to install it with `dnf`. Anoter way is to use pip

### Fedora

```bash
sudo dnf install ansible
```

### Python

```bash
pip install ansible
```


## Running a playbook
Retrieve the roles from GIT
```bash
ansible-galaxy install -r requirements.yml -p roles/
```


Run the playbook
```bash
cd <dir>
ansible-playbook -i inventory -K basic-setup.yml -e "ansible_user=<remote_user>"
```
