# ansible_ping
This is shortest ansible command for pinging server

Many a times we are lazy to write playbook and need a quick work around to ping server/s

### Command
Syntax
ansible all -i __"ip seperate by comma and an extra comma at the end"__ -m ping --user __user_to_connect_to_server__ --become-user=sudo
  
``
ansible all -i "127.0.0.1," -m ping --user dhavlev --become-user=sudo
``
