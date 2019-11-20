# Ansible deployment docker

This script will deploy this project : [https://github.com/anthonykgross/rabbitmq-symfony-python](https://github.com/anthonykgross/rabbitmq-symfony-python)

## Installation
```bash
pip3 install -r requirements.txt
```

## Usage
```bash
ansible-playbook -i inventories/production site.yml -c paramiko --ask-pass
```


## Creator
**Anthony K GROSS**
- <http://anthonykgross.fr>
- <https://twitter.com/anthonykgross>
- <https://github.com/anthonykgross>

## Copyright and license
Code and documentation copyright 2020. Code released under [MIT License](LICENSE).
