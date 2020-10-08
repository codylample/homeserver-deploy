# homeserver-deploy
Ansible playbooks for deploying my home server.

To deploy:
```
# Unlock bitwarden vault
bw unlock

# Run ansible playbook
ansible-playbook -i inventories/home playbook.yaml
```
