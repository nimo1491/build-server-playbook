# build-server-playbook

My Ansible playbooks for managing build server easily.

## Usage

*Install development required packages*

```bash
ansible-playbook playbooks/install_pkg.yml
```

*Create an user*

```bash
ansible-playbook playbooks/create_user.yml --extra-vars="username=test_user password=test_password"
```

*Delete an user*

```bash
ansible-playbook playbooks/delete_user.yml --extra-vars="username=test_user"
```

