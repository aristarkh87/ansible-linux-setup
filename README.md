# Getting started

## Requirements

* git
* python3 `>= 3.5`
* python3-virtualenv
* ansible `>= 2.5`

## Installation

1. Setup virtualenv:
    ```
    virtualenv -p python3 --system-site-packages ./ansible
    source ./ansible/bin/activate
    ```

2. Install Ansible and run playbook:
    ```
    pip install -r requirements.txt
    ansible-playbook ${parameters} playbook.yml
    ```

    for example:
    ```
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
