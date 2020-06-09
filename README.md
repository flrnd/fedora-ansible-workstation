# Fedora Linux Workstation ansible playbooks
A collection of personal playbooks to customize a fresh Fedora install.
You need to install [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html "Official ansible installation guide") to run these playbooks.

Feel free to try it in a virtual machine before using it in your own workstation.

#### Command line

```shell
$ ansible-pull -u $(whoami) -K -U https://github.com/flrnd/ansible.git
```

#### Test

```shell
$ ansible-pull -u $(whoami) -K -U https://github.com/flrnd/ansible.git --check
```
