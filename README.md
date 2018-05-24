# Ansible playbooks for macOS

These playbooks were written to quickly set up my preferred development
environment for macOS.

`setup.yml` installs Z Shell with Oh My Zsh and sets up my dotfiles from a Git repository.

## Getting started

First, install [Homebrew](https://brew.sh/).

```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Next, install Ansible using Homebrew

```
$ brew install ansible
```

Finally, clone this repository and run the initial setup playbook.

```
$ git clone git@github.com:weimeng/ansible-macos.git
$ cd ansible-macos
$ ansible-playbook setup.yml
```