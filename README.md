# Ansible Linux Setup
[![Build Status](https://travis-ci.org/aristarkh87/ansible-linux-setup.svg?branch=master)](https://travis-ci.org/aristarkh87/ansible-linux-setup)

# Getting started

## Requirements

* git
* python3 `>= 3.5`
* python3-venv
* ansible `>= 2.8`

## Installation

1. Setup venv:
    ```
    python3 -m venv --system-site-packages ansible
    source ansible/bin/activate
    ```

2. Install Ansible and run playbook:
    ```
    pip install ansible
    ansible-playbook ${parameters} playbook.yml
    ```

    for example:
    ```
    ansible-playbook playbook.yml
    ansible-playbook --tags iptables playbook.yml
    ```

3. Deactivate Ansible
    ```
    deactivate
    ```

## Tags

* software
* iptables
* automount
* nano
* vim
* grub
* backlight
