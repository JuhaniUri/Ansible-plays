# Ansible-play

# Role: create-user-with-password

- creates user(s) 
- adds to user group
- create random password for user. 
- force user to change it a first login
- saves the password to file

Variables are in create-user-with-password.yml.
"pwgen" must be installed to master server (from where you run the ansible)

To run: ansible-playbook create-user-with-password.yml -i environments/dev/oracle-vm-inventory
