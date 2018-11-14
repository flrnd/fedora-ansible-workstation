# Workstation ansible playbooks
================================

First of all, you'll need ansible [installed in your local machine](https://docs.ansible.com/ansible/2.5/installation_guide/intro_installation.html "Official ansible installation guide").

### commandline

options:

-b (become)
-K (ask for become-password)

```shell
$ ansible-playbook -bK localhost.yml
```


