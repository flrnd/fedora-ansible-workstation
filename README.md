# Workstation ansible playbooks

Need ansible [installed in your local machine](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html "Official ansible installation guide").

#### Command line

```shell
$ ansible-pull -u $(whoami) -K -U https://github.com/flrnd/ansible.git
```

###### Testing:

```shell
$ ansible-pull -u $(whoami) -K -U https://github.com/flrnd/ansible.git --check
```
