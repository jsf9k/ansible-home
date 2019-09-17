# ansible-home #

Ansible code to configure and maintain my home network.  The code here
assumes that all devices have been installed via
[jsf9k/ansible-arch-install](https://github.com/jsf9k/ansible-arch-install)
or
[jsf9k/ansible-raspi-install](https://github.com/jsf9k/ansible-raspi-install).

## Usage ##

Populate `inventory.yml` and run `site.yml`:

```console
ansible-playbook -i inventory.yml site.yml
```

To update all packages, run `update.yml`:
```console
ansible-playbook -i inventory.yml update.yml
```
