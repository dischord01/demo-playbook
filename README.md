# NGC-Ansible-Playbook
`NGC-Ansible-Playbook` is a great ansible playbook.

# Install Ansible Roles from [Galaxy](https://galaxy.ansible.com/)

```
ansible-galaxy install username.rolename
```


# Usage
## Development (if you used `--vagrant` flag: `vagrant up`

Run `vagrant provision` to provision your vms with Ansible.

## Production
`ansible-playbook -i inventory site.yml`
