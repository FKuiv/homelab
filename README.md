# Collection of everything I self host

Currently it includes my homelab and blog site.

Check the inventory.example.ini for how to structure hosts for ansible.

## Commands

Run a playbook:
`ansible-playbook playbooks/homelab.yml -i inventory.ini`

Run a playbook while setting the hosts:
`ansible-playbook playbooks/setup_docker.yml -i inventory.ini --extra-vars "host=blog"`
