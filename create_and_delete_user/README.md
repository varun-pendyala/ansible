# ansible

Create on each server (file hosts in /etc/ansible/hosts) users from the list (file users.yml).

Add the public key in public_kays dir (username.pub).
In users.yml specify that user should have the right to sudo or not.

# run below commands to create or delete users

ansible-playbook create_user.yml
ansible-playbook delete_user.yml
