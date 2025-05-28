# Fedora Linux Workstation ansible playbook

Personal playbook for fresh Fedora installs.

## Introduction

I started using ansible few years ago because I hate repeating some tasks every time I have to setup a new Workstation.
With ansible I can provision a Workstation ready to my daily needs:

* Install a few packages, like tilix, ripgrep, bat, virt-manager, etc.
* Set my default shell to ~~zsh~~ fish and clone my [dotfiles](https://github.com/flrnd/dotfiles).
* ~~Activate RPM Fusion repositories and install ffmpeg and some non-free goodies~~ (Deprecated, you can enable third party repos).
* Install Visual Studio Code.
* Clone forgit

### Usage example

Note: You can use any of the configured tags to filter any of the imported playbooks, this example focused on the packages flow.

**Run everything**: ansible-playbook local.yml

**Only install packages**: ansible-playbook local.yml --tags packages

**Only configure shell**: ansible-playbook local.yml --tags shell

**Skip package upgrades**: ansible-playbook local.yml --skip-tags upgrade
