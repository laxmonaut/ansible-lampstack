# ansible-lampstack
Anisble Playbook to configure LAMP stack
# I created this playbook while practicing Ansible

Steps:
1. Install Ansible
2. Modify the exising inventory file.
3. Run the following commands:
  a. ansible-playbook lampStack-playbook.yml -i inventory
  b. ansible-playbook mariadb-cfg-playbook.yml -i inventory
4. Chck the website using the IP address of the server at port 80.
