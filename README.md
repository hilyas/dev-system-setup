# dev-system-setup

Ansible playbook to configure a local development system. This is a work in progress, and it's my personal setup, use at your own risk.

To run the playbook, navigate to the `dev-system-setup` directory and run the following command:

```sh
ansible-playbook playbook.yml -K
```

The `inventory.yml` file is there for reference only, as this playbook is used for local runs primarily.
Likewise, `group_vars/` and `host_vars/` can be used to store variable files specific to host groups or individual hosts.

## Tests

tbd

## Roles

### `common_cli_tools`

tbd

### `cask_application`

tbd

### `oh-my-zsh`

tbd

### `docker`

Install the role from Ansible Galaxy:

```sh
ansible-galaxy install geerlingguy.docker
```

Or install using the requirements.yml file:

```sh
ansible-galaxy install -r requirements.yml
```

This command will install the roles listed in the `requirements.yml` file into the default roles path or the one specified in your project's `ansible.cfg` file.