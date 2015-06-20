# ansible-playbooks

ansiblerole is a simple script to create an ansible playbook skeleton.
add the file to your path, enable execute (set +x /usr/local/bin/ansiblerole)

Directories and files created:
 * /etc/ansible/roles/<role>
 * /etc/ansible/roles/<role>/files
   * /etc/ansible/roles/<role>/files/skeleton_file
 * /etc/ansible/roles/<role>/tasks
   * /etc/ansible/roles/<role>/tasks/main.yml
 * /etc/ansible/roles/<role>/vars
   * /etc/ansible/roles/<role>/vars/main.yml


#### To use: 
ansiblerole adduser
```
----------------------------------------------
Creating skeleton for: adduser
Creating directory: /etc/ansible/roles/adduser
Creating directory: /etc/ansible/roles/adduser/files
Creating directory: /etc/ansible/roles/adduser/tasks
Creating directory: /etc/ansible/roles/adduser/vars
Creating file: /etc/ansible/roles/adduser/files/skeleton_file
Creating file: /etc/ansible/roles/adduser/tasks/main.yml
Creating file: /etc/ansible/roles/adduser/vars/main.yml
----------------------------------------------
[Success] role adduser created
```
