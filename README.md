# GoPhish-Ansible-Setup

This Playbook is designed to configure a new host by install Go and GoPhish.

Works with Ansible v2.8
Make sure to add the host name or IP to the host you are executing this playbook from to /etc/ansible/hosts.
You may need to change the default username in /GoPhish/vars/main.yml
Run this with `ansible-playbook -K GoPhish-Ansible-Setup.yml` and provide the password for the user on the localhost that you want to sudo as.

No support is provided.

The playbook was created by modifying existing playbooks created by:

Jordan Wright https://github.com/gophish/gophish.git
Joshua Lund https://github.com/jlund/ansible-go.git

