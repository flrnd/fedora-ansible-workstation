# Fedora Linux Workstation ansible playbook
Personal playbook for fresh Fedora installs.

## Introduction

I started using ansible few years ago because I hate repeating some tasks every time I have to setup a new Workstation.
With ansible I can provision a Workstation ready to my daily needs:

* Install a few packages, like tilix, ripgrep, bat, virt-manager, etc.
* Set my default shell to zsh and clone my [dotfiles](https://github.com/flrnd/dotfiles).
* Activate RPM Fusion repositories and install ffmpeg and some non-free goodies.
* Install Visual Studio Code.

#### Command line

```shell
$ ansible-pull -u $(whoami) -K -U https://github.com/flrnd/ansible.git
```

#### Test

```shell
$ ansible-pull -u $(whoami) -K -U https://github.com/flrnd/ansible.git --check
```
