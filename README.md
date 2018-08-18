# Getting started

## Requirements

* git
* python3 `>= 3.5`
* virtualenv
* ansible `>= 2.4`

## Installation

1. Setup virtualenv:
    ```
    virtualenv -p python3 --system-site-packages ./ansible
    source ./ansible/bin/activate
    ```

2. Install Ansible and run playbook:
    ```
    pip install ansible ansible-lint
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
