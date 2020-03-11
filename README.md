# check_config
# Command:
ansible-playbook -i inventory.yml check_acl.yml -k ansible_ssh_extra_args='-o StrictHostKeyChecking=no' -v
