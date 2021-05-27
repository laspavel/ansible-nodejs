# Ansible role for install NODEJS

## Configurating

   - /vars/main.yml - install parameters (node version, modules etc.)
   - inventory.ini - hosts for install

## Run

ansible-playbook -i inventory.ini nodejs_deploy.yml

